# CSS Cascade Specificity and Inheritance

> In all the below rules the order of applied color will be from top to bottom so the last one will be applied

## 1. Position
```css
li{
    color: red;
    color: blue;
}
```

## 2. Specificity
```css
li {color:blue;}
.first-class {color: red;}
li[draggable] {color: purple;}
#first-id {color: orange;}
```

## 3. Type
```css
<link rel="stylesheet" href="./style.css"> (External)
<style></style> (Internal)
<h1 style=" ">Hello</h1> (Inline)
```

# 4. Importance
```css
color: red;
color: green !important;
```


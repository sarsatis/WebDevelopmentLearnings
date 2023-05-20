# CSS Combining

# 1. Group

```css
selector, selector {
    color: blueboilet;
}

e.g
h1,h2 {
  color: blueviolet;
}
```

# 2. Child
> Child = Apply to direct child of left side. i.e 1st child
```css
selector > selector {
    color: firebrick;
}

e.g All the below are same
div > p {
    color: firebrick;
}
OR
div > .done {
    color: firebrick;
}
OR
.box > .done {
    color: firebrick;
}
```

# 3. Descendent (Ancestor selector)

```css
selector selector{
    color: blue
}

e.g
> li selector can be any level below the tree

.box li {
    color: blue
}
```

# 4. Chaining

> Chaining =  Apply where all selectors are true

```css
selectorselector{
    color: seagreen;
}

e.g

<h1 id="title" class="big heading">Hello World</h1>

h1#title.big.heading{
    color: seagreen;
}
```

# 5. Combining Combiners

> We are combining ancestor and chaining combiniers
```css
ul p.done{
    font-size: 0.5rem;
}
```


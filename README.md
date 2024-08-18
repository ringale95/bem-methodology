# BEM Methodology

## What is BEM?

The Block, Element, Modifier methodology (commonly referred to as BEM) is a popular naming convention for classes in HTML and CSS.

Examples:

```
/* Block component */
.btn {}

/* Element that depends upon the block */ 
.btn__price {}

/* Modifier that changes the style of the block */
.btn--orange {} 
.btn--big {}
```

In CSS, <code>block</code> is top level abstraction of new component.Example: <code>button  .btn{}</code>.

Child items are placed inside these and are denoted by two underscores following name of block
```
.btn__price{}
```

Finally, modifiers can manipulate block so that we can style particular component without inflicting
changes on unrelated module.

```
.btn--orange{}
```
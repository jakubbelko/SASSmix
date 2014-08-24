SASSmix
=======

Library SASS mixins that I use as the basis of all coded pages and templates.

@mixin clearfix
---------------

@mixin prefixer
---------------

@mixin bg-color
---------------

example to use: 
```scss
@include bg-color(rgba(0, 0, 0, 0.75), 0.9);
```

result:
```css
background-color: #000000;
background-color: rgba(0, 0, 0, 0.75);
```


@mixin text-color
-----------------

example to use: 
```scss
@include text-color(rgba(0, 0, 0, 0.75), 0.9);
```

result:
```css
color: #000000;
color: rgba(0, 0, 0, 0.75);
```

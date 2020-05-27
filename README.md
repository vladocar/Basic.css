[![License MIT](https://img.shields.io/badge/licence-MIT-blue.svg)](https://choosealicense.com/licenses/mit/)
[![Gzip Size](https://img.badgesize.io/https://unpkg.com/@vladocar/basic.css@1.0.0/css/basic.min.css?compression=gzip)](https://unpkg.com/@vladocar/basic.css@1.0.0/css/basic.min.css)


Basic.css
=======================================

Classless CSS Starter File

* * *

Basic.css gives you basic CSS formatting and ability to make basic grids with only HTML5 syntax.

### List of features

*   Lightweight 1kb minified and gzipped.
*   Basic Typography.
*   Basic Forms.
*   Custom colors.
*   Dark theme.
*   Round corners.
*   Flex Grid without classes.
*   Flex Grid cards.

This project uses the best parts from my previous projects:

https://github.com/vladocar/Basic-CSS-Typography-Reset

https://github.com/vladocar/infinity-css-grid

https://github.com/vladocar/Simple-Button

##### Change root css variables with your color palette

```css
:root{
--c1:#0074d9;
--c2:#eee;
--c3:#fff;
--c4:#000;
--c5:#fff;
}
```

##### Adjust the round corners

By default are 8px, use --rc: 0px; if you don't like round corners.

```css
:root{
--rc: 8px;
}
```

##### Override the colors in the dark mode:

```css
@media (prefers-color-scheme: dark) {
	:root {
        --c2:#333;
        --c3:#1e1f20;
        --c4:#fff;
	}
}
```

##### How you can use the infinity flex grid?

Use the HTML5 tags selection and aside to make flex grid.

```html
<section>
  <aside> 1 </aside>
	<aside> 2 </aside>
	<aside> 3 </aside>
</section>
<section>
	<aside> 1 </aside>
	<aside> 2 </aside>
	<aside> 3 </aside>
	<aside> 4 </aside>
</section>
```

Use the HTML5 tags selection and article to make cards.

```html
<section>
    <article> 1 </article>
    <article> 2 </article>
    <article> 3 </article>
</section>
```

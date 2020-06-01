[![License MIT](https://img.shields.io/badge/licence-MIT-blue.svg)](https://choosealicense.com/licenses/mit/)
[![Gzip Size](https://img.badgesize.io/https://unpkg.com/@vladocar/basic.css@1.0.1/css/basic.min.css?compression=gzip)](https://unpkg.com/@vladocar/basic.css@1.0.1/css/basic.min.css)


Basic.css
=======================================

Classless CSS Starter File

* * *

Basic.css gives you basic CSS formatting and ability to make basic grids with only HTML5 syntax. You can use this project to Set your default styling.

### List of features

*   Lightweight 1kb minified and gzipped.
*   Basic typography.
*   Basic forms.
*   Custom colors.
*   Dark theme.
*   Round corners.
*   Flex Grid without classes.
*   Flex Grid cards.

Demo: https://vladocar.github.io/Basic.css/

This project uses the best elements from my previous projects:

https://github.com/vladocar/Basic-CSS-Typography-Reset  
https://github.com/vladocar/infinity-css-grid  
https://github.com/vladocar/Simple-Button  

##### You can change root css variables with your color palette:

```css
:root{
--c1:#0074d9;
--c2:#eee;
--c3:#fff;
--c4:#000;
--c5:#fff;
}
```

##### Or adjust the round corners

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
Demo: https://vladocar.github.io/Basic.css/grid.html

Use the HTML5 tags selection and article to make cards.

```html
<section>
    <article> 1 </article>
    <article> 2 </article>
    <article> 3 </article>
</section>
```
Demo: https://vladocar.github.io/Basic.css/cards.html

#### How to use this project?

Simply download and personalize the **basic.css** file.

Or

```sh
npm i @vladocar/basic.css
```

#### Why should you use this project?

Instead of using CSS Reset you could just Set the basic css formatting and styling. You could even make some grids with the HTML5 tags. Naturally if you want to build something more complex you should use CSS classes and this project works great in combination with other CSS frameworks.



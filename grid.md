Grid System
=======================================
***

###Simple Grid

The simple grid is based on this code:


```css
section{display: flex; flex-flow: row wrap}
section {flex:1}
```
And the HTML looks like this:

```html
<section>
	<section> 1 </section>
	<section> 2 </section>
	<section> 3 </section>
</section>
<section>
	<section> 1 </section>
	<section> 2 </section>
	<section> 3 </section>
	<section> 4 </section>
</section>
```
You can add as many columns as you like. 

It is based on my previous Infinity CSS Grid https://github.com/vladocar/infinity-css-grid .

###Complex Grid

It wasn't my attention to make classless complex grid. CSS classes are perfect for making grids. Use classes for grids.

But [@sylvainpolletvillard](https://github.com/sylvainpolletvillard) made very interesting [pull request](https://github.com/vladocar/Basic.css/pull/2) using next level CSS "hacks". It gives dynamic almost JavaScript capabilities to the CSS code.

I'm talking about this code:

```css
[style*="--c:"] {flex:var(--c,1)}
```

And is used like this:

```html
<section>
	<section> 1 </section>
	<section style = "--c:3"> Merge 3 columns </section>
	<section> 3 </section>
</section>
```

Or:

```html
<section>
	<div style = "--c:1"></div>
	<div style = "--c:2"></div>
	<div style = "--c:1"></div>
</section>
```
Demo [grid.html](grid.html)

Basically with the variable  --c you can control the number of columns you like to merge.

 style = "--c:4"  means you will unite(merge) the width of 4 columns.

 Ok, I admit it, it looks ugly. But, it works.

 Probably Morty (Rick and Morty) comment would be:
 "It looks like CSS class framework with extra steps".




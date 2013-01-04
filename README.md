Little Grid
================

Little Grid isn't like your average CSS grid. There are only two classes, `row` and `column`. This means you don't have to worry about remembering class names, and you can spend more time working on a sweet design.

Because there are only two classes, you can define your own widths and sizes super easily, and the grid will take care of the messy part, and they will always work.

With Little Grid, you can infinitely nest columns. And you don't have to worry about breakpoints for most of it. Little Grid is built on the principals of mobile first design, and rapid prototyping. Also, Little Grid has fluid columns with fixed gutters! Your sites will look better than ever.

Anything lower than IE 8, will get a usable 1-column design.

**[View Demo](http://bradp.github.com/little-grid)** 

###Example

```html
<div class="row">
	<div class="column content"> Lorem Ipsum </div>
	<div class="column sidebar"> Lorem Ipsum </div>
</div>
```
Because this grid gives you the freedom to make your own layout, you also need to do some CSS work

```css
@media only screen and (min-width: 30em) {
	.content { width: 75%; }
	.sidebar { width: 25%; }
}
```

####Browser Support

Because we are going mobile-first, any non-supported browser will still end up with a very usable site, albeit only one column. The biggest problem would be the `box-sizing` property, but IE9 and up support it. 

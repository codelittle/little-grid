little-grid
===========

A Minimal Responsive Grid For Your Everyday Use


## Basic Usage

The grid begins with a `.row`. Columns are specified with classes `columns-#` and `large-#`. Columns live inside rows and won’t work correctly if used outside rows.

```html
<div class="row">
	<div class="columns-6 large-12">
		6 columns wide on medium and 12 columns on large
	</div>
	<div class="columns-3 large-6">
		3 columns wide on medium and 6 columns on large
	</div>
	<div class="columns-3 large-6">
		3 columns wide on medium and 6 columns on large
	</div>
	<div class="columns-12">
		when you only use columns-# it applies to both medium and large
	</div>
</div>
```

## Nesting Grids

You can have a grid within a grid within a grid within a grid. This can be very useful sometimes, but nest carefully to keep your markup clean.

```html
<div class="row">
	<div class="columns-12 large-12">
		<h1>Nesting Grids</h1>
		<div class="row">
			<div class="columns-6 large-6">
				<p>Nested Left Half</p>
			</div>
			<div class="columns-6 large-6">
				<p>Nested Right Half</p>
			</div>
		</div>
		<!-- closed .row -->
	</div>
</div>
<!-- closed .row -->
```

Enjoy, and I hope you use this for your next project.
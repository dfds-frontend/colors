# DFDS colors

## main colors from CDN

load the font by inluding this in html

```html
 <link rel="stylesheet"
       href="https://unpkg.com/@kunukn/dfds-colors/dist/colors.css">
```

or import it from css

```html
<style>
  @import "https://unpkg.com/@kunukn/dfds-colors/dist/colors.css";
</style>
```

use the colors in css

```css
.button--primary {
	color: var(--color-white);
	background-color: var(--color-primary-orange);
}
```

use the styling

```html
<button class="button button--primary">Click here</button>
```

## main colors from npm

-   npm install @kunukn/dfds-colors
-   the files are in node_modules/@kunukn/dfds-colors/dist

load it inluding this in html

```html
<link rel="stylesheet"
      href="node_modules/@kunukn/dfds-colors/dist/colors.css">
```

## demo

-   https://codepen.io/kunukn/full/805042b2e7c7a6d1b0d1f6d490476f59 cdn js, color list
-   https://codepen.io/kunukn/full/156ac0afa402c5d780437ce9c3f8027c cdn css var usage
-   https://codesandbox.io/s/8lx5r4onl9 npm, color list

## more

To see all the available CDN files go to

https://unpkg.com/@kunukn/dfds-colors/

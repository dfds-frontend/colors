# DFDS colors

## main colors from CDN

load the font by inluding this in html

```html
 <link rel="stylesheet"
       href="https://unpkg.com/@dfds-frontend/colors/dist/colors.css">
```

or import it from css

```html
<style>
  @import "https://unpkg.com/@dfds-frontend/colors/dist/colors.css";
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

-   npm install @dfds-frontend/colors
-   the files are in node_modules/@dfds-frontend/colors/dist

load it inluding this in html

```html
<link rel="stylesheet"
      href="node_modules/@dfds-frontend/colors/dist/colors.css">
```

## demo

-   https://codepen.io/kunukn/full/67da1197b74e4030606a79c18e638e0c/ cdn js, color list
-   https://codepen.io/kunukn/pen/f30321d67af72011cf1b87dd64ea0070 cdn css var usage
-   https://codesandbox.io/s/6yq09864k3 npm, color list

## more

To see all the available CDN files go to

https://unpkg.com/@dfds-frontend/colors/

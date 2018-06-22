# Animation Library
Pure CSS Animation Library. Made with love at Later.com

1. Simple add css or scss files to your project
2. Apply animation class to animate an element

## Basic Usage

1. Link the stylesheet to your document's `<head>`

```html
<head>
  <link rel="stylesheet" type="text/css" href="animation-library-min.css">
</head>
```
2. Add the animation class to the HTML element you'd like to animate.
```html
<div class="u--fadeIn" >...</div>
```
3. List of avialable animation classes:

| Fade              | Slide            | Bounce              | Flip        | Rotate               | Zoom             | Attention    |
| :---------------- | :--------------- | :------------------ | :---------- | :------------------- | :--------------- | :----------- |
| `u--fadeIn`       | `u--slideUp`     | `u--bounceIn`       | `u--flip`   | `u--rotate`          | `u--zoomIn`      | `u--pulse `  |
| `u--fadeInLeft`   | `u--slideDown `  | `u--bounceOut`      | `u--flipX`  | `u--rotateUpLeft`    | `u--zoomInDown`  | `u--flash `  |
| `u--fadeInRight`  | `u--slideLeft`   | `u--bounceInLeft`   | `u--flipY ` | `u--rotateUpRight`   | `u--zoomInUp`    | `u--bounce ` |
| `u--fadeInUp`     | `u--slideRight`  | `u--bounceInRight`  |             | `u--rotateDownLeft`  | `u--zoomOut`     | `u--shake `  |
| `u--fadeInDown`   |                  | `u--bounceInUp`     |             | `u--rotateDownRight` | `u--zoomOutDown` | `u--swing `  |
| `u--fadeOut`      |                  | `u--bounceInDown`   |             |                      | `u--zoomOutUp`   |              |
| `u--fadeOutLeft`  |                  |                     |             |                      |                  |              |
| `u--fadeOutRight` |                  |                     |             |                      |                  |              |
| `u--fadeOutUp`    |                  |                     |             |                      |                  |              |
| `u--fadeOutDown`  |                  |                     |             |                      |                  |              |

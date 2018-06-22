# Animation Library
Pure CSS Animation Library. Made with love at [Later.com](https://later.com)

1. Simply add css or scss files to your project
2. Apply animation class to animate an element
3. [Live Demo](http://animation.kaustubhmenon.com)

## Basic Usage

1. Link the stylesheet to your document's `<head>`

```html
<head>
  <link rel="stylesheet" type="text/css" href="animation-library-min.css">
</head>
```
2. Add the animation class to the HTML element you'd like to animate.
```html
<div class="u--fadeIn " >Animation Library</div>
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

## Contributing

1. Please create a pull request
2. Do not commit directly to master
3. Follow current class naming convention(BEM)
```html
<style>
  .u--camelCaseName {}
</style>
```
4. Create a [pen](http://codepen.io) to showcase the animation if possible :)

## Credits

- [anime.js](http://anime-js.com/) by Julian Garnier
- [imagesLoaded](http://imagesloaded.desandro.com/) by Dave DeSandro
- [Charming.js](https://github.com/yuanqing/charming) by Yuan Qing

# Color Scale

### This repo is a simple color scale created using the power of Sass.

Look through the code, you will get the idea pretty quick. I will put more instructions in here soon, pinky swear.

In the mean time `bower install color-scale` to get it in there. And then in your `gruntfile.js` add the following when using `grunt-sass`:

```js
options: {
  includePaths: [
    './bower_components/color-scale'
  ]
}
```

Then import into your primary Sass manifest file:

```scss
@import "color-scale";
```

# PostCSS Smart Variables [![Build Status][ci-img]][ci]

[PostCSS] plugin for using variables in color functions.

[PostCSS]: https://github.com/postcss/postcss
[ci-img]:  https://travis-ci.org/dainemawer/postcss-smart-variables.svg
[ci]:      https://travis-ci.org/dainemawer/postcss-smart-variables

```css

:root {
    --primary-color: #FF0000;
}

.foo {
    background-color: color( var(--primary-color) blackness(60%));
}
```

```css
.foo {
  background-color: #990000
}
```

## Usage

```js
postcss([ require('postcss-smart-variables') ])
```

See [PostCSS] docs for examples for your environment.

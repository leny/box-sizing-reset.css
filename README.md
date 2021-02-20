# box-sizing-reset.css

> Just the simple [box-sizing reset](https://www.paulirish.com/2012/box-sizing-border-box-ftw/), as plain css, in npm.

* * *

## Usage

Install with `npm install box-sizing-reset.css`.

Use in your app with 

```js
import "box-sizing-reset.css;
```

## Content

It's simply the plain [box-sizing reset](https://www.paulirish.com/2012/box-sizing-border-box-ftw/), as following:

```css
html {
  box-sizing: border-box;
}
*, *:before, *:after {
  box-sizing: inherit;
}
```
* * *
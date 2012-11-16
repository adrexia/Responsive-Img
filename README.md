Responsive-Img
==============

Responsive Img is a jQuery plugin that changes an image's src attribute based on its container's width.

The plugin requires only 2 files.

## Documentation

### Basic usage

```javascript
$("img").responsiveImg();

or

$("img").responsiveImg({
  breakpoints : {
    "_small":360,
    "_medium":780,
    "_large":900
  },
  srcAttribute : "src",
  pathToPHP : "js",
  createNewImages : true
});
```

### Default Options

```javascript
{
	breakpoints : {
    "_small":360,
    "_medium":780,
    "_large":900
  },
  srcAttribute : "src",
  pathToPHP : "js",
  createNewImages : true
}
```
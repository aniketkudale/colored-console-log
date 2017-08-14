# colored-console-log

A JavaScript API module, which allows app to log colored console logs in browser console.

[![NPM](https://nodei.co/npm/colored-console-log.png?downloads=true)](https://nodei.co/npm/colored-console-log/)

**[DEMO](http://www.aniket.co/labs/cc-logs/demo/)**

## Installation
Installing this module is pretty easy using npm:

```python
npm install colored-console-log
```
Then just add the module into your HTML:

In your `HTML`

```HTML
<script src="../js/colored-console-log.js"></script>
```

## Usage
You can print colored logs in browser console using any of these three functions:

Using `colored.logs()`

```javascript
colored.logs("This text will have red font-color and black background.", "red", "black");
```

Using `color.logs()`

```javascript
color.logs("This text will have yellow font-color and blue background.", "yellow", "blue");
```

Using `cc.logs()`

```javascript
cc.logs("This text will have #00FF00 font-color and #000000 background.", "#00FF00", "#000000");
```

Customizable / Optional parameters:

`colored.logs(Text, Font-color, Background-color)`

## Parameters

- **Text**: [String] Message you want to display in console log.
- **Font-color**: [String][Optional] Font color of text in log, can be HEX value. Default is Black.
- **Background-color**: [String][Optional] Background color text in log, can be HEX value. Default is White

You can use these function parameters in folowing ways:

```javascript
colored.logs("This text will have red font-color and white(default) background.", "red");

color.logs("This text will have black(default) font-color and blue background.", "", "blue");

cc.logs("This text will have black(default) font-color and white(default) background.");
```

## License
MIT

jquery.mobile.swipe
===================

A [jQuery Mobile](http://jquerymobile.com/) plugin that makes it easier to include a [Swipe](http://swipejs.com/) component in your app.


Installation
------------

1. Download the [latest release](https://github.com/philippbosch/jquery.mobile.swipe/releases).
2. Unzip.
3. Copy `jquery.mobile.swipe.js` to your project's javascript directory.
4. Include the file in your HTML code, e.g. `<script src="js/jquery.mobile.swipe.min.js"></script>` after the jQuery Mobile JavaScript, like so:

```html
<script src="js/jquery.min.js"></script>
<script src="js/jquery.mobile.min.js"></script>
<script src="js/jquery.mobile.swipe.js"></script>
```


Basic Usage
-----------

In your HTML file use the widget like this:

```html
<div data-role="swipe">
    <div>My first slide</div>
    <div>My second slide</div>
    <div>My third slide</div>
</div>
```

You are, of course, free to put whatever you want in your slides. The slides do not necessarily have to be `<div>`s. Here is an example with images:

```html
<div data-role="swipe">
    <img src="img/image1.jpg">
    <img src="img/image2.jpg">
    <img src="img/image3.jpg">
</div>
```


You can customize the swipe widget with the following `data-` attributes:

| Attribute          | Description                                             | Example                                |
|--------------------|---------------------------------------------------------|----------------------------------------|
| `data-start-slide` | Index position Swipe should start at (default: 0)       | `data-start-slide="3"`                 |
| `data-speed`       | Speed of prev and next transitions in ms (default: 300) | `data-speed="500"`                     |
| `data-auto`        | Begin with auto slideshow (time in ms between slides)   | `data-auto="2000"`                     |



License
-------

[MIT](http://philippbosch.mit-license.org/)

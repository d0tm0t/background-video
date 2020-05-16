Fullscreen HTML5 Background Video
======================
> This plugin will help you play a video on a container.

[![GitHub license](https://img.shields.io/github/license/d0tm0t/background-video.svg)](https://github.com/d0tm0t/background-video/blob/master/LICENSE)
![Author](https://img.shields.io/badge/author-%40d0tm0t-blue.svg)

# Demo
[**Example page**](http://d0tm0t.github.io/background-video/)

Features
--------

### Resizing

The `container` element in use will automatically adapt to the container's dimensions. It will also resize as the browser window resizes.

### Overlay

Plugin doesn't supports any overlay as it is easy to implement that with plain HTML/CSS.

### Video Cover

Video might take a few seconds to load, especially because the sources are added via JS which is something you'll load after the DOM's loading. Till then you may want to show a video cover which'll be same as the first frame or the video (or some other image).

The support for this is not in the plugin as it's fairly simple to achieve this via just HTML/CSS (just like overlays). Check the example!

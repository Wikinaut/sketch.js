# Sketch.js

This is a fork of @intridea Sketch.js library. Sketch.js is an easy-to-use jQuery plugin that allows you to create canvases upon
 which visitors can draw. The code is partially inspired by <a href='http://www.williammalone.com/articles/create-html5-canvas-javascript-drawing-app/'>William Malone's drawing app tutorial</a> as well as <a href='http://canvaspaint.org'>CanvasPaint</a>.

## Features of this fork

- Correct canvas resize handling. All your drawings are resized along with canvas.
- Custom backgrounds with correct export and download handling.
- A method to undo last drawing action.
- Removed original CoffeeScript source.
- Removed original "toolLinks" functions, since they're unneeded when you can simply call methods like $('canvas').sketch('method', 'value').

## Future plans

As this library is used on one of my projects and author of the original doesn't accept pull requests, I'll maintain it as long as the project is alive.

So, I plan to implement this functionality:

- Retina @2X pixel density support.
- Text input with simple html tags support (like b, u, i, etc.).
- Fix some compability problems.
- Correct eraser handling.

Feel free to submit any issues, I'll try to fix the problems when I have time.

## Installation

To use Sketch.js in your project, just grab the latest version from GitHub and include it in your project after jQuery.

## License

Copyright (C) 2011 by Michael Bleigh and Intridea, Inc.
Copyright (C) 2017 by Ruslan Slinkov

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

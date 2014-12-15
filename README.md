# Shadershop

http://tobyschachman.com/Shadershop/

Shadershop is an interface for programming GPU shaders in the mode of a direct manipulation image editor like Photoshop. It is an experiment in leveraging the programmer’s spatial reasoning the way that coding today leverages the programmer’s symbolic reasoning.

## Build Instructions

Install [node.js](http://nodejs.org/) and [coffeescript](http://coffeescript.org/).

Run `npm install` in this directory to install the development dependencies.

Run `coffee build.coffee` to build. It will compile the files in `src` into `compiled/app.js` and `compiled/app.css`. It will also automatically watch for changes in `src` files and recompile as necessary.

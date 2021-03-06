# CG Assignment

## Install
Before you begin, make sure you are comfortable with terminal commands and have [Node and NPM installed](https://www.npmjs.com/get-npm).
```bash
npm install
```

## Running the development server
To see the changes you make to the starter project go to the project folder in terminal and type...

```bash
npm start
```

This command will bundle the project code and start a development server at [http://localhost:8080/](http://localhost:8080/).

## Editing the code
The first file you should open is `./objects/Scene.js`. In it you will find the 4 objects comprising the world represented in your browser. The bowling ball, bowling pin, the island, and the lights illuminating them are each represented as a javascript file in the `./object/s` folder.
Create other folders for your parts, and export to scene.js, then you can find your objects in browser. If something goes wrong a message will displayed in the debug console of the browser.

## Importing local files
Local files, such as images and 3D models, are imported into the application as URLs then loaded asynchronously with three.js. Most common files that three.js uses are supported. Shader files are loaded as raw text. For more information about this system see the [webpack site](https://webpack.js.org/).


You can copy the land.js and change it to your objects.

## Importing modules from the web
If you want to add additional functionality to your project, you can search and install them from the [NPM repository](https://www.npmjs.com/). Some modules you might want to consider are...
* [three-orbit-controls](https://www.npmjs.com/package/three-orbit-controls)
* [popmotion](https://www.npmjs.com/package/popmotion)
* [Cannon.js Physics](https://www.npmjs.com/package/cannon).

Additions like these are best managed in the projects entry file: `./src/entry.js`. In it are the Scene, Camera, Renderer, the window event listeners and the animation loop.


## License
[MIT](https://github.com/edwinwebb/three-seed/blob/master/LICENSE)

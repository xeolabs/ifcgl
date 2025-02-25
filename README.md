# xeometry

**xeometry** is an open source \(MIT\) JavaScript library from [@xeographics](https://twitter.com/xeographics) for viewing and interacting with 3D glTF models on WebGL. 

Use it to build 3D viewer apps and custom interactive presentations of glTF content, or as a boilerplate to bootstrap the development of your own 3D viewer.

* [Programming Guide](https://xeolabs.gitbooks.io/xeometry-guide/content/)
* [API Docs](http://xeometry.org/docs/#viewer)
* [Examples](http://xeometry.org/examples)
* [Downloads](https://github.com/xeolabs/xeometry/releases)
* [Source code](https://github.com/xeolabs/xeometry)

[![](http://xeolabs.com/xeometry/assets/transparency.png)](http://xeolabs.com/xeometry/examples/#effects_transparency)

````javascript
var viewer = new xeometry.Viewer({ canvasId: "theCanvas" });

viewer.loadModel("saw", "models/Reciprocating_Saw.gltf", function () {
     viewer.setOpacity(["saw#0", "saw#1", "saw#2", "saw#3", "saw#11"], 0.3);
     viewer.viewFit("saw");
});
````
\[ [_Run this example_](http://xeolabs.com/xeometry/examples/#effects_transparency) \]

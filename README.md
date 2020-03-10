# Monaco Editor Webpack Example

* First of all, run "npm i" to install packages.

* Then run webpack to bundle file.

* Afterward you can test the index.html in browser.

* Notice: You have to run index.html with a mock Server (Not directly from file system) (I use the Live Server Extension in Visual Studio Code). Because Monaco Editor use Webworker and HTML5 doesn't let Javascript initiate a Webworker within file system
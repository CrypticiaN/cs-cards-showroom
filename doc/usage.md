## Basic structure

```
.
├── css
│   ├── main.css
│   └── normalize.css
├── doc
├── img
├── js
│   └── main.js
├── .editorconfig
├── 404.html
├── browserconfig.xml
├── index.html
├── package.json
├── site.webmanifest
```

What follows is a general overview of each major part and how to use them.

### css

This directory should contain all your project's CSS files. 

### doc

This directory contains all the HTML5 Boilerplate documentation. You can use it
as the location and basis for your own project's documentation.

### js

This directory should contain all your project's JS files. Libraries, plugins,
and custom code can all be included here. It includes some initial JS to help
get you started. [About the JavaScript](js.md).

### 404.html

A helpful custom 404 to get you started.

### .editorconfig

The `.editorconfig` file is provided in order to encourage and help you and your
team to maintain consistent coding styles between different editors and IDEs.
[Read more about the `.editorconfig` file](misc.md#editorconfig).

### index.html

This is the default HTML skeleton that should form the basis of all pages on
your site. If you are using a server-side templating framework, then you will
need to integrate this starting HTML with your setup.

Make sure that you update the URLs for the referenced CSS and JavaScript if you
modify the directory structure at all.

If you are using Google Universal Analytics, make sure that you edit the
corresponding snippet at the bottom to include your analytics ID.

### package.json

Edit this file to describe your application, add dependencies, scripts and
other properties related to node based development and the npm registry
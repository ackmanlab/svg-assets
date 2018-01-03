The goal of this project is to provide a repository that contains scalable vector graphics (svg) content for open usage by our research group and the greater public community.

All content in this repo should be contributed with the intention of being openly shared and compatible with the Creative Commons Public domain license [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/).

This repo will be made public after initial setup.

### What is svg?

[Scalable Vector Graphics](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics) is an open W3C standard for 2D vector graphics exchange over the world wide web. It is just a plain text markup (xml) specification. SVG graphics files can be opened and edited in any text editor, can be rendered in any web browser, and can be created from many free or proprietary graphics programs. In the context of a web page application, svg can be styled with CSS and scripted/animated with JavaScript.


### Notes

The type of svg graphics added to this git repo should primarily be a mix of simple line drawings, shading, and text. *Usage of raster/image data should be minimized.* Though svg files can contain images-- either as embedded data or as a hypertext link to remote url-- embedded images get encoded as a [base64 data format](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Data_URIs) in svg graphics files. Base64 is a highly portable, but less efficient (e.g wasteful) way of storing real image data compared with raster formats like png/jpeg). Thus if the desired content does not require too many objects, it should be composed as a vector graphic

Graphics from here can then be openly patched into more complex figure/svg graphics for other projects.

All are welcome to contribute. The free and open source [Inkscape](https://inkscape.org) drawing program is highly recommended for creating or editing svg graphics figures. Libreoffice has some nice diagramming tools as well. Graphviz (dot language) is good for diagrams of networks.

<!-- Recommended workflow is to clone this repo locally, then make a working branch for yourself separate from the master branch while working on collaborative changes or adding new content. Then merge the changes with master. -->
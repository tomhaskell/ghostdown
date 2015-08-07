# Ghostdown 
This is an attempt to clone the [Ghost](http://ghost.org) blogging platform's editor. The idea is simple - write your content using the simple [Markdown](http://daringfireball.net/projects/markdown/) format, and see a live preview at the same time.

## Usage
The `index.html` file contains a usage example with styling and layout, but it's really very easy. Simply download the [repository](https://github.com/thlabs/ghostdown) (or just the `scripts\ghostdown.js` file). *Ghostdown* is setup to use [Require.js](http://requirejs.org), so include the following line in your html file:

```html
<script type="text/javascript" data-main="scripts/ghostdown" src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.20/require.min.js"></script>
```

### Image uploading

![Placeholder for image]

## Libraries
*Ghostdown* is built on the following existing libraries:

* [CodeMirror](http://codemirror.net) - for editing and syntax highlighting of the Markdown content
* [showdown](https://github.com/showdownjs/showdown) - to translate the markdown into the live preview
* [Dropzone](http://www.dropzonejs.com/) - to simplify image uploading

### Credits
Based on some initial work by [Shawn Xie](https://github.com/fengluo/ghostdown)
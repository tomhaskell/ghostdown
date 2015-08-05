# Ghostdown 
This is an attempt to clone the [Ghost](http://ghost.org) blogging platform's editor. The idea is simple - write your content using the simple [Markdown]() format, and see a live preview at the same time.

![Relax with a coffee](https://as1.ftcdn.net/jpg/00/69/28/76/500_F_69287640_oKhSm7NcuIb3miPyx64LU4veg6US0x3e.jpg) 

## Usage
The `index.html` file contains a usage example with styling and layout, but it's really very easy. Simply download the [repository](https://github.com/thlabs/ghostdown) (or just the `scripts\ghostdown.js` file). *Ghostdown* is setup to use [Require.js](http://requirejs.org), so include the following line in your html file:

```html
<script type="text/javascript" data-main="scripts/ghostdown" src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.20/require.min.js"></script>
```

### Image uploading

![Placeholder for image]

## Libraries
*Ghostdown* is built on the following existing libraries:

* [CodeMirror](http://codemirror.net) - for editing and syntax highlighting the Markdown content
* [showdown]() - to translate the markdown into the live preview
* [Dropzone]() - to simplify image uploading

## Licence
Based on some initial work by [Shawn Xie](https://github.com/fengluo/ghostdown)
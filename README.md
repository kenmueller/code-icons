> File specific icons for the browser from Atom File-icons, https://github.com/file-icons/atom

[![Hyperapp demo](https://img.shields.io/badge/File%20icons%20demo-%E2%86%92-9D6EB3.svg?style=flat-square)](https://websemantics.github.io/file-icons-js)

<img alt="Icon previews" width="850" src="https://raw.githubusercontent.com/file-icons/atom/6714706f268e257100e03c9eb52819cb97ad570b/preview.png" />

## Install

Use `npm` to install as follows,

```bash
npm i websemantics/file-icons-js
```

Or, `Bower`,

```bash
bower i websemantics/file-icons-js
```

## Getting Started

Include `css` styles from `styles/index.css` in the header of an html document.

Get an instance of `FileIcons` class,

```js
const icons = window.FileIcons
```

Get the class name of the icon that represent a filename (for example `text-icon`),

```js
const filename = 'src/app.js'
const class_name = icons.getClass(filename)
```

You can also get a class name of the associated icon color,

```js
const filename = 'README.md'
const class_name = icons.getClassWithColor(filename)
```

Use the class name to generate html, for example,

```js
document.body.innerHTML = '<a><i class=' + class_name + '></i>$filename</a>'
```

## Resources

- [Atom File Icons](https://github.com/file-icons/atom), file specific icons for improved visual grepping.
- [Markdown Browser Plus](https://github.com/websemantics/markdown-browser-plus), Github flavoured, local file browser for markdown docs.

# code-icons

> File specific icons for the browser from Atom File-icons, https://github.com/file-icons/atom

[![Hyperapp demo](https://img.shields.io/badge/File%20icons%20demo-%E2%86%92-9D6EB3.svg?style=flat-square)](https://websemantics.github.io/file-icons-js)

<img alt="Icon previews" width="850" src="https://raw.githubusercontent.com/file-icons/atom/6714706f268e257100e03c9eb52819cb97ad570b/preview.png" />

## Install

```bash
npm i code-icons
```

## Include CSS styles

```js
import 'code-icons/styles.css'
```

## Get `className`

```js
import icons from 'code-icons'

const className = icons.getClass('src/app.js')
const className = icons.getClassWithColor('README.md')

document.body.innerHTML += `<span class="${className}"></span>`
```

## Resources

- [Atom File Icons](https://github.com/file-icons/atom), file specific icons for improved visual grepping.
- [Markdown Browser Plus](https://github.com/websemantics/markdown-browser-plus), Github flavoured, local file browser for markdown docs.

# docsify-katex

[![jsdelivr](https://data.jsdelivr.com/v1/package/npm/docsify-katex/badge)](https://www.jsdelivr.com/package/npm/docsify-katex)
[![npm bundle size (minified)](https://img.shields.io/github/size/upupming/docsify-katex/dist/docsify-katex.js.svg?style=flat-square)](https://www.npmjs.com/package/docsify-katex)
[![npm](https://img.shields.io/npm/v/docsify-katex.svg?style=flat-square)](https://www.npmjs.com/package/docsify-katex)

Add [KaTeX](https://github.com/KaTeX/KaTeX/) support to your docsify project.

## Usage

Add `docsify-katex` JS and CSS scripts to your `index.html`:

```html
<script src="//cdn.jsdelivr.net/npm/katex@latest/dist/katex.min.js"></script>
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/katex@latest/dist/katex.min.css" />
<script src="//cdn.jsdelivr.net/npm/marked@4"></script>

<!-- CDN files for docsify-katex -->
<script src="//cdn.jsdelivr.net/npm/docsify-katex@latest/dist/docsify-katex.js"></script>
<!-- or <script src="//cdn.jsdelivr.net/gh/upupming/docsify-katex@latest/dist/docsify-katex.js"></script> -->
```

Note:

1. `gh/upupming/docsify-katex@latest/dist/docsify-katex.js` will always fetch the latest version of `docsify-katex` on GitHub, you can use it when you want to try the latest dev features.

## Demo projects

|             Name              |                                    Website                                    |                                        Source code                                        |
| :---------------------------: | :---------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------: |
| `docsify-katex` documentation | [junxnone.github.io/docsify-katex/docs](https://junxnone.github.io/docsify-katex/docs/) | [upupming/docsify-katex/docs](https://github.com/upupming/docsify-katex/tree/master/docs) |
|           Firebook            |       [yngtodd.github.io/firebook](https://yngtodd.github.io/firebook/)       |                  [yngtodd/firebook](https://github.com/yngtodd/firebook)                  |

If you have an awesome project using `docsify-katex` and want to share it with others, please leave it at [this issue](https://github.com/upupming/docsify-katex/issues/7). I will add it here as soon as possible.

## LaTeX quick reference

- [Supported functions](supported)
- [Support table](support-table)
- [Detexify](http://detexify.kirelabs.org/classify.html)
- [MathJax quick reference on Stack Exchange](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

## Inspired by

1. [vscode-markdown](https://github.com/yzhang-gh/vscode-markdown)
2. [yzhang-gh/markdown-it-katex](https://github.com/yzhang-gh/markdown-it-katex)

## Credits

1. [KaTeX](https://github.com/Khan/KaTeX)

## Known issues

Making KaTeX work properly with docsify is a hard work, this repo is just a workaround. We used an extra `marked` instance to do the syntax parsing.

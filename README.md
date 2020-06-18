# JSTL Language Support [<img src="https://github.com/jsxtools/jstl-language/raw/master/icon.png" alt="JSTL" width="90" height="90" align="right">][JSTL Language Support]

[<img height="20" alt="Installs" src="https://img.shields.io/visual-studio-marketplace/i/jsxtools.jstl">](https://marketplace.visualstudio.com/items?itemName=jsxtools.jstl)
[<img height="20" alt="Rating" src="https://img.shields.io/visual-studio-marketplace/stars/jsxtools.jstl">](https://marketplace.visualstudio.com/items?itemName=jsxtools.jstl)
[<img height="20" alt="Support Chat" src="https://img.shields.io/badge/support-chat-blue.svg">](https://gitter.im/postcss/postcss)

[JSTL Language Support] adds support for JavaScript Template Literal files in **Visual Studio Code**.

```jstl
---
title: JSTL Support
features:
- slim and flexible
- better for configuration
---
<!doctype html>
<html>
  <head>
    <title>${title}</title>
  </head>
  <body>
    <h1>${title}</h1>
    <ul>
      ${features.map(feature => (
        <li>{feature.toUpperCase()}!</li>
      ))}
    </ul>
  </body>
</html>
```

This syntax is applied to `.jstl` files. It is also applied to `jstl` code blocks in Markdown, and also to `<script type=text/jstl>` code blocks in HTML.

## Usage

JavaScript Template Literal files can be used in:

- [Eleventy](https://www.11ty.dev/docs/languages/jstl/) ([sample](https://github.com/11ty/eleventy-sample-jstl))

## Installation

1. Open the command palette and select **Extensions: Install Extensions**
2. Search for **JSTL Language Support**
3. Click **Install**

[JSTL Language support]: https://github.com/jsxtools/jstl-language

# &lt;CodePen /&gt;

> A react component to embed [codepen](http://codepen.io)

English | [简体中文](./README.zh-CN.md)

## Getting Started

```bash
# NPM
$ npm install react-codepen-box -S
$ npm install prop-types -S

# Yarn
$ yarn add react-codepen-box
$ yarn add prop-types
```

## Usage

```js
import React from 'react'
import CodePen from 'react-codepen-box'

export default class CodeBox extends React.Component {
  render() {
    return (
      <CodePen
        user="leedom92"
        hash="gOLvgRe"
      />
    )
  }
}
```

## Options

Property | Type     | Argument     | Values                   | Default   | Description
---------|----------|--------------|--------------------------|-----------|------------
type     | `string` | `<optional>` | `iframe, embed`          | `iframe`  | the type of the [codepen](http://codepen.io).
user     | `string` | `<required>` |                          | `null`    | codepen username.
hash     | `string` | `<required>` |                          | `null`    | the hash id of the pen to display.
width    | `string` | `<optional>` | `'', %`                  | `100%`    | the width of the pen.
height   | `string` | `<optional>` | `'', %`                  | `400`     | the height of the pen.
title    | `string` | `<optional>` |                          | `''`      | the title of the pen.
theme    | `string` | `<optional>` |  `light, dark`           | `light`   | the theme the pen should use.
editable | `bool`   | `<optional>` | `true, false`            | `true`    | the editable of the pen.
tab      | `string` | `<optional>` | `html, css, js, result`  | `result`  | the default tab that should be displayed.

## License
Copyright (c) 2021 [Leedom](https://github.com/leedom92)  
Licensed under the MIT license.

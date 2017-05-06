[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/daKmoR/grain-masonry)
[![Polymer Version](https://img.shields.io/badge/polymer-v2-blue.svg)](https://www.polymer-project.org)

# \<grain-masonry\>

Wrapper for the amazing masonry grid. (https://masonry.desandro.com/)

## Demo
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="grain-masonry.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<grain-masonry transition-duration="250">
  <article style="height: 30px;">Power</article>
  <article style="height: 50px;">To</article>
  <article style="height: 25px;">The</article>
  <article style="height: 35px;">People</article>
  <article style="height: 40px;">!</article>
</grain-masonry>
<style>
  article {
    background: #36abcc; width: 29%; margin: 2%; color: #fff; display: flex; align-items: center; justify-content: center;
  }
</style>
```

## Installation

```sh
$ bower install --save daKmoR/grain-masonry
```

## Getting Started

Import the package.

```html
<link rel="import" href="/bower_components/grain-masonry/grain-masonry.html">
```

*For more information, see the API documentation.*

## Working on the Element

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed.
* View the Element via `polymer serve`
* Run tests via `polymer test`

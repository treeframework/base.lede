# Lede

The `lede` module provides a very small amount of additional styles for
paragraphs.

## Dependencies

The `lede` module depends on two other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tools.font-size](https://github.com/treeframework/tools.font-size)

## Installation

You can install `lede` module via Bower, npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-lede --save
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "bower_components/tree-lede/trump.lede";
```

### Install using npm:

```sh
$ npm install tree-lede --save
```

### Install via file download

The least recommended option for installation is to simply download
`_trump.lede.scss` into your project and `@import` it into your project in its
Trump layer.

## Usage

Basic usage of the `lede` module uses the required clasess:

```html
<p class="u-lede">...</p>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.

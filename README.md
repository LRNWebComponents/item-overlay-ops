<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="item-overlay-ops.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<item-overlay-ops add edit remove duplicate move edit-mode>
  <paper-card heading="Title of the thing" image="stock.jpg" elevation="2" animated-shadow="false">
    <div class="card-content">This is some content of a card</div>
  </paper-card>
</item-overlay-ops>
```
[Video talking about this element](https://www.youtube.com/watch?v=Fxpdxn5mu_I)

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/LRNWebComponents/item-overlay-ops)

# \<item-overlay-ops\>

A LRN element

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

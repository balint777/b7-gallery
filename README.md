[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/balint777/b7-gallery)

# \<b7-gallery\>

# Demo
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="b7-gallery.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<style>
    img {
        width: 100px;
    }
</style>

<b7-gallery target-selector='img.gallery-item'></b7-gallery>

<img class="gallery-item"
    src="https://picsum.photos/100/100?image=10"
    data-url="https://picsum.photos/1920/1080?image=10"/>
<img class="gallery-item"
    src="https://picsum.photos/100/100?image=11"
    data-url="https://picsum.photos/1920/1080?image=11"/>
<img class="gallery-item"
    src="https://picsum.photos/100/100?image=12"
    data-url="https://picsum.photos/1920/1080?image=12"/>
<img class="gallery-item"
    src="https://picsum.photos/100/100?image=13"
    data-url="https://picsum.photos/1920/1080?image=13"/>
<img class="gallery-item"
    src="https://picsum.photos/100/100?image=14"
    data-url="https://picsum.photos/1920/1080?image=14"/>
```


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

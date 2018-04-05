[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/balint777/b7-gallery)

# \<b7-gallery\>

# 'Anchor tag based graceful fallback' practice using b7-gallery
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <style>
        body {
            min-height: 20em;
        }
    </style>
    <link rel="import" href="b7-gallery.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html

<b7-gallery trigger-selector='a'></b7-gallery>

<a href="https://picsum.photos/1920/1080?image=10">
    <img src="https://picsum.photos/100/100?image=10"/>
</a>
<a href="https://picsum.photos/1920/1080?image=11">
    <img src="https://picsum.photos/100/100?image=11"/>
</a>
<a href="https://picsum.photos/1920/1080?image=12">
    <img src="https://picsum.photos/100/100?image=12"/>
</a>
<a href="https://picsum.photos/1920/1080?image=13">
    <img src="https://picsum.photos/100/100?image=13"/>
</a>
<a href="https://picsum.photos/1920/1080?image=14">
    <img src="https://picsum.photos/100/100?image=14"/>
</a>
```

# Demo
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <style>
        body {
            min-height: 20em;
        }
    </style>
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

<b7-gallery trigger-selector='img.gallery-item' url-attribute='data-url'></b7-gallery>

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

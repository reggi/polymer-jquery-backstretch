# Polymer jQuery Backstretch

## Installation

```
bower install reggi/polymer-jquery-backstretch --save
```

## Usage

Drop the following lines within the `<head>` tag.

	<script src="./bower_components/platform/platform.js"></script>
	<link rel="import" href="./bower_components/polymer-github-ribbon/github-ribbon.html">

To create a new image use the `<jquery-backstretch>` tag.

	<jquery-backstretch src="https://cdn.shopify.com/s/files/1/0031/5352/files/IMG_8960.JPG?25987"></jquery-backstretch>

## Attributes

### `src`

The url of the image. (required)

> Note: A `width` is required to contain the blocked div. If the image isn't appearing on the screen it's due to the fact that the parent div that `<jquery-backstretch>` is contained has a `height` or `width` value that is set to `0`.

Source: [Backstretch](http://srobbin.com/jquery-plugins/backstretch/) (Scott Robbin)
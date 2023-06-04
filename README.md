# WebFont Roboto

Package for integrating `Roboto` fonts in a web environment.

![npm](https://img.shields.io/npm/v/@wikiline/webfont-roboto?style=for-the-badge)
![npm](https://img.shields.io/npm/dm/@wikiline/webfont-roboto?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@wikiline/webfont-roboto?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @wikiline/webfont-roboto
 ```

## Usage (CSS)

CSS files are located in the `root` directory:

* `all.css`
* `all.min.css`
* `all-normal.css`
* `all-normal.min.css`
* `all-italic.css`
* `all-italic.min.css`

Font files are located in the `fonts/` directory.

### Importing

To import all fonts, you can use:

```css
@import "~@wikiline/webfont-roboto/all.css";
@import "~@wikiline/webfont-roboto/all.min.css";
@import "~@wikiline/webfont-roboto/all-normal.css";
@import "~@wikiline/webfont-roboto/all-normal.min.css";
@import "~@wikiline/webfont-roboto/all-italic.css";
@import "~@wikiline/webfont-roboto/all-italic.min.css";
```

To import specific fonts, you can use:

```css
@import "~@wikiline/webfont-roboto/typefaces/100.css";
@import "~@wikiline/webfont-roboto/typefaces/100.min.css";
@import "~@wikiline/webfont-roboto/typefaces/100-normal.css";
@import "~@wikiline/webfont-roboto/typefaces/100-normal.min.css";
@import "~@wikiline/webfont-roboto/typefaces/100-italic.css";
@import "~@wikiline/webfont-roboto/typefaces/100-italic.min.css";
@import "~@wikiline/webfont-roboto/typefaces/300.css";
@import "~@wikiline/webfont-roboto/typefaces/300.min.css";
@import "~@wikiline/webfont-roboto/typefaces/300-normal.css";
@import "~@wikiline/webfont-roboto/typefaces/300-normal.min.css";
@import "~@wikiline/webfont-roboto/typefaces/300-italic.css";
@import "~@wikiline/webfont-roboto/typefaces/300-italic.min.css";
@import "~@wikiline/webfont-roboto/typefaces/400.css";
@import "~@wikiline/webfont-roboto/typefaces/400.min.css";
@import "~@wikiline/webfont-roboto/typefaces/400-normal.css";
@import "~@wikiline/webfont-roboto/typefaces/400-normal.min.css";
@import "~@wikiline/webfont-roboto/typefaces/400-italic.css";
@import "~@wikiline/webfont-roboto/typefaces/400-italic.min.css";
@import "~@wikiline/webfont-roboto/typefaces/500.css";
@import "~@wikiline/webfont-roboto/typefaces/500.min.css";
@import "~@wikiline/webfont-roboto/typefaces/500-normal.css";
@import "~@wikiline/webfont-roboto/typefaces/500-normal.min.css";
@import "~@wikiline/webfont-roboto/typefaces/500-italic.css";
@import "~@wikiline/webfont-roboto/typefaces/500-italic.min.css";
@import "~@wikiline/webfont-roboto/typefaces/700.css";
@import "~@wikiline/webfont-roboto/typefaces/700.min.css";
@import "~@wikiline/webfont-roboto/typefaces/700-normal.css";
@import "~@wikiline/webfont-roboto/typefaces/700-normal.min.css";
@import "~@wikiline/webfont-roboto/typefaces/700-italic.css";
@import "~@wikiline/webfont-roboto/typefaces/700-italic.min.css";
@import "~@wikiline/webfont-roboto/typefaces/900.css";
@import "~@wikiline/webfont-roboto/typefaces/900.min.css";
@import "~@wikiline/webfont-roboto/typefaces/900-normal.css";
@import "~@wikiline/webfont-roboto/typefaces/900-normal.min.css";
@import "~@wikiline/webfont-roboto/typefaces/900-italic.css";
@import "~@wikiline/webfont-roboto/typefaces/900-italic.min.css";
```

```css
body {
    font-family: 'Roboto', sans-serif;
}
```

### Variables

Each font uses the following CSS variables to set the font display property with the default `swap` value if CSS
variables are not defined:

* `--font-display` global value applicable to all fonts
* `--font-display-roboto` the value applicable to a specific font

```css
:root {
    --font-display: swap;
    --font-display-roboto: swap;
}
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the SIL
Open Font License, v1.1. Some fonts use the Apache 2 license. The Ubuntu fonts use the Ubuntu Font License v1.0.

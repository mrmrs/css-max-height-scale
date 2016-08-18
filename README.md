# css-max-height-scale 0.0.6

Css module of single purpose classes for max height scale

#### Stats

301 | 40 | 40
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-max-height-scale
```

#### With Git

```
git clone https://github.com/tachyons-css/css-max-height-scale
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-max-height-scale";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-max-height-scale">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   MAX HEIGHTS - SCALE
*/
.mxhi1 { max-height: 1rem; }
.mxhi2 { max-height: 2rem; }
.mxhi3 { max-height: 4rem; }
.mxhi4 { max-height: 8rem; }
.mxhi5 { max-height: 16rem; }
.mxhi6 { max-height: 32rem; }
.mxhi7 { max-height: 48rem; }
.mxhi8 { max-height: 64rem; }
.mxhi9 { max-height: 96rem; }
.mxhi10 { max-height: 128rem; }
@media screen and (min-width: 48em) {
 .mxhi1-ns { max-height: 1rem; }
 .mxhi2-ns { max-height: 2rem; }
 .mxhi3-ns { max-height: 4rem; }
 .mxhi4-ns { max-height: 8rem; }
 .mxhi5-ns { max-height: 16rem; }
 .mxhi6-ns { max-height: 32rem; }
 .mxhi7-ns { max-height: 48rem; }
 .mxhi8-ns { max-height: 64rem; }
 .mxhi9-ns { max-height: 96rem; }
 .mxhi10-ns { max-height: 128rem; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .mxhi1-m { max-height: 1rem; }
 .mxhi2-m { max-height: 2rem; }
 .mxhi3-m { max-height: 4rem; }
 .mxhi4-m { max-height: 8rem; }
 .mxhi5-m { max-height: 16rem; }
 .mxhi6-m { max-height: 32rem; }
 .mxhi7-m { max-height: 48rem; }
 .mxhi8-m { max-height: 64rem; }
 .mxhi9-m { max-height: 96rem; }
 .mxhi10-m { max-height: 128rem; }
}
@media screen and (min-width: 64em) {
 .mxhi1-l { max-height: 1rem; }
 .mxhi2-l { max-height: 2rem; }
 .mxhi3-l { max-height: 4rem; }
 .mxhi4-l { max-height: 8rem; }
 .mxhi5-l { max-height: 16rem; }
 .mxhi6-l { max-height: 32rem; }
 .mxhi7-l { max-height: 48rem; }
 .mxhi8-l { max-height: 64rem; }
 .mxhi9-l { max-height: 96rem; }
 .mxhi10-l { max-height: 128rem; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC

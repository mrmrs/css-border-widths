# css-border-widths 1.0.6

Css module of single purpose classes for border widths

#### Stats

693 | 120 | 120
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-border-widths
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-border-widths
```

ssh:
```
git clone git@github.com:tachyons-css/css-border-widths.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-border-widths";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-border-widths@1.0.6/css/css-border-widths.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-border-widths">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   BORDER WIDTHS

   LEGEND

   b = border

   a = all
   t = top
   b = bottom
   l = left
   r = right

   w = width

   0-5 = step in sizing scale

*/
.baw0 { border-width: 0; }
.baw1 { border-width: .125rem; }
.baw2 { border-width: .25rem; }
.baw3 { border-width: .5rem; }
.baw4 { border-width: .75rem; }
.baw5 { border-width: 1rem; }
.btw0 { border-top-width: 0; }
.btw1 { border-top-width: .125rem; }
.btw2 { border-top-width: .25rem; }
.btw3 { border-top-width: .5rem; }
.btw4 { border-top-width: .75rem; }
.btw5 { border-top-width: 1rem; }
.bbw0 { border-bottom-width: 0; }
.bbw1 { border-bottom-width: .125rem; }
.bbw2 { border-bottom-width: .25rem; }
.bbw3 { border-bottom-width: .5rem; }
.bbw4 { border-bottom-width: .75rem; }
.bbw5 { border-bottom-width: 1rem; }
.blw0 { border-left-width: 0; }
.blw1 { border-left-width: .125rem; }
.blw2 { border-left-width: .25rem; }
.blw3 { border-left-width: .5rem; }
.blw4 { border-left-width: .75rem; }
.blw5 { border-left-width: 1rem; }
.brw0 { border-right-width: 0; }
.brw1 { border-right-width: .125rem; }
.brw2 { border-right-width: .25rem; }
.brw3 { border-right-width: .5rem; }
.brw4 { border-right-width: .75rem; }
.brw5 { border-right-width: 1rem; }
@media screen and (min-width: 48em) {
 .baw0-ns { border-width: 0; }
 .baw1-ns { border-width: .125rem; }
 .baw2-ns { border-width: .25rem; }
 .baw3-ns { border-width: .25rem; }
 .baw4-ns { border-width: .75rem; }
 .baw5-ns { border-width: 1rem; }
 .btw0-ns { border-top-width: 0; }
 .btw1-ns { border-top-width: .125rem; }
 .btw2-ns { border-top-width: .25rem; }
 .btw3-ns { border-top-width: .5rem; }
 .btw4-ns { border-top-width: .75rem; }
 .btw5-ns { border-top-width: 1rem; }
 .bbw0-ns { border-bottom-width: 0; }
 .bbw1-ns { border-bottom-width: .125rem; }
 .bbw2-ns { border-bottom-width: .25rem; }
 .bbw3-ns { border-bottom-width: .5rem; }
 .bbw4-ns { border-bottom-width: .75rem; }
 .bbw5-ns { border-bottom-width: 1rem; }
 .blw0-ns { border-left-width: 0; }
 .blw1-ns { border-left-width: .125rem; }
 .blw2-ns { border-left-width: .25rem; }
 .blw3-ns { border-left-width: .5rem; }
 .blw4-ns { border-left-width: .75rem; }
 .blw5-ns { border-left-width: 1rem; }
 .brw0-ns { border-right-width: 0; }
 .brw1-ns { border-right-width: .125rem; }
 .brw2-ns { border-right-width: .25rem; }
 .brw3-ns { border-right-width: .5rem; }
 .brw4-ns { border-right-width: .75rem; }
 .brw5-ns { border-right-width: 1rem; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .baw0-m { border-width: 0; }
 .baw1-m { border-width: .125rem; }
 .baw2-m { border-width: .25rem; }
 .baw3-m { border-width: .5rem; }
 .baw4-m { border-width: .75rem; }
 .baw5-m { border-width: 1rem; }
 .btw0-m { border-top-width: 0; }
 .btw1-m { border-top-width: .125rem; }
 .btw2-m { border-top-width: .25rem; }
 .btw3-m { border-top-width: .5rem; }
 .btw4-m { border-top-width: .75rem; }
 .btw5-m { border-top-width: 1rem; }
 .bbw0-m { border-bottom-width: 0; }
 .bbw1-m { border-bottom-width: .125rem; }
 .bbw2-m { border-bottom-width: .25rem; }
 .bbw3-m { border-bottom-width: .5rem; }
 .bbw4-m { border-bottom-width: .75rem; }
 .bbw5-m { border-bottom-width: 1rem; }
 .blw0-m { border-left-width: 0; }
 .blw1-m { border-left-width: .125rem; }
 .blw2-m { border-left-width: .25rem; }
 .blw3-m { border-left-width: .5rem; }
 .blw4-m { border-left-width: .75rem; }
 .blw5-m { border-left-width: 1rem; }
 .brw0-m { border-right-width: 0; }
 .brw1-m { border-right-width: .125rem; }
 .brw2-m { border-right-width: .25rem; }
 .brw3-m { border-right-width: .5rem; }
 .brw4-m { border-right-width: .75rem; }
 .brw5-m { border-right-width: 1rem; }
}
@media screen and (min-width: 64em) {
 .baw0-l { border-width: 0; }
 .baw1-l { border-width: .125rem; }
 .baw2-l { border-width: .25rem; }
 .baw3-l { border-width: .5rem; }
 .baw4-l { border-width: .75rem; }
 .baw5-l { border-width: 1rem; }
 .btw0-l { border-top-width: 0; }
 .btw1-l { border-top-width: .125rem; }
 .btw2-l { border-top-width: .25rem; }
 .btw3-l { border-top-width: .5rem; }
 .btw4-l { border-top-width: .75rem; }
 .btw5-l { border-top-width: 1rem; }
 .bbw0-l { border-bottom-width: 0; }
 .bbw1-l { border-bottom-width: .125rem; }
 .bbw2-l { border-bottom-width: .25rem; }
 .bbw3-l { border-bottom-width: .5rem; }
 .bbw4-l { border-bottom-width: .75rem; }
 .bbw5-l { border-bottom-width: 1rem; }
 .blw0-l { border-left-width: 0; }
 .blw1-l { border-left-width: .125rem; }
 .blw2-l { border-left-width: .25rem; }
 .blw3-l { border-left-width: .5rem; }
 .blw4-l { border-left-width: .75rem; }
 .blw5-l { border-left-width: 1rem; }
 .brw0-l { border-right-width: 0; }
 .brw1-l { border-right-width: .125rem; }
 .brw2-l { border-right-width: .25rem; }
 .brw3-l { border-right-width: .5rem; }
 .brw4-l { border-right-width: .75rem; }
 .brw5-l { border-right-width: 1rem; }
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


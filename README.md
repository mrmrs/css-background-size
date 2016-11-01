# css-background-size 1.0.6

Css module of single purpose classes for background size

#### Stats

290 | 28 | 28
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-background-size
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-background-size
```

ssh:
```
git clone git@github.com:tachyons-css/css-background-size.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-background-size";
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
<link rel="stylesheet" href="http://unpkg.com/css-background-size@1.0.6/css/css-background-size.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-background-size">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   BACKGROUND SIZE
*/
.bg-cv { background-size: cover; }
.bg-cn { background-size: contain; }
.bg-quarter { background-size: 25%; }
.bg-half { background-size: 50%; }
.bg-three-quarters { background-size: 75%; }
.bg-full { background-size: 100%; }
.bg-auto { background-size: auto; }
@media screen and (min-width: 48em) {
 .bg-cv-ns { background-size: cover; }
 .bg-cn-ns { background-size: contain; }
 .bg-quarter-ns { background-size: 25%; }
 .bg-half-ns { background-size: 50%; }
 .bg-three-quarters-ns { background-size: 75%; }
 .bg-full-ns { background-size: 100%; }
 .bg-auto-ns { background-size: auto; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .bg-cv-m { background-size: cover; }
 .bg-cn-m { background-size: contain; }
 .bg-quarter-m { background-size: 25%; }
 .bg-half-m { background-size: 50%; }
 .bg-three-quarters-m { background-size: 75%; }
 .bg-full-m { background-size: 100%; }
 .bg-auto-m { background-size: auto; }
}
@media screen and (min-width: 64em) {
 .bg-cv-l { background-size: cover; }
 .bg-cn-l { background-size: contain; }
 .bg-quarter-l { background-size: 25%; }
 .bg-half-l { background-size: 50%; }
 .bg-three-quarters-l { background-size: 75%; }
 .bg-full-l { background-size: 100%; }
 .bg-auto-l { background-size: auto; }
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


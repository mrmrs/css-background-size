# CSS BACKGROUND SIZE

  Mobile-first classes for css-background-size.
  Set the desired css-background-size on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-background-size
```
or download the css on github and include in your project.


## File Size

1.6K background-size.css
1.0K background-size.min.css

## The Code
```
  .bg-cv  {             background-size: cover; }
  .bg-cn  {             background-size: contain; }
  .bg-quarter {         background-size: 25%; }
  .bg-half {            background-size: 50%; }
  .bg-three-quarters {  background-size: 75%; }
  .bg-full {            background-size: 100%; }
  .bg-auto {            background-size: auto; }

@media screen and (min-width: 48em) {
  .bg-cv-ns {             background-size: cover; }
  .bg-cn-ns {             background-size: contain; }
  .bg-quarter-ns {         background-size: 25%; }
  .bg-half-ns {            background-size: 50%; }
  .bg-three-quarters-ns {  background-size: 75%; }
  .bg-full-ns {            background-size: 100%; }
  .bg-auto-ns {            background-size: auto; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .bg-cv-m {             background-size: cover; }
  .bg-cn-m {             background-size: contain; }
  .bg-quarter-m {         background-size: 25%; }
  .bg-half-m {            background-size: 50%; }
  .bg-three-quarters-m {  background-size: 75%; }
  .bg-full-m {            background-size: 100%; }
  .bg-auto-m {            background-size: auto; }
}

@media screen and (min-width: 64em)  {
  .bg-cv-l {             background-size: cover; }
  .bg-cn-l {             background-size: contain; }
  .bg-quarter-l {         background-size: 25%; }
  .bg-half-l {            background-size: 50%; }
  .bg-three-quarters-l {  background-size: 75%; }
  .bg-full-l {            background-size: 100%; }
  .bg-auto-l {            background-size: auto; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


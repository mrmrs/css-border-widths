# CSS BORDER WIDTHS

  Mobile-first classes for css-border-widths.
  Set the desired css-border-widths on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-border-widths
```
or download the css on github and include in your project.

## File Size


## The Code
```
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

@media screen and (min-width: 48em) and (max-width: 64em) {
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

@media screen and (min-width: 64em)  {
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


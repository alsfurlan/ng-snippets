# ng-snippets

Snippets for Sublime Text (by [@alsfurlan] (https://github.com/alsfurlan)) and Vim (by [@brunoti] (https://github.com/brunoti)) with all the main features of AngularJS based on [John Papa's Angular Style Guide] (https://github.com/johnpapa/angular-styleguide).

## Using with Sublime Text

1. Clone this repo inside the user packages folder. 
```shell
git clone https://github.com/alsfurlan/ng-snippets.git
```
2. Go to `Preferences >  Browse Packages... > User` and paste the `sublime-text` folder content.

### Snippets
To use this snipets enter one of this shortcuts on a JavasScript file:

```shell
ngconfig
ngconstant
ngcontroller
ngdirective
ngfactory
ngmodule
ngservice
```

## Using with Vim

1. Install [neosnippet] (https://github.com/Shougo/neosnippet.vim) or [snipMate] (https://github.com/garbas/vim-snipmate) plugin on your vim.
2. Clone this repo:
```shell
git clone https://github.com/alsfurlan/ng-snippets.git
```
3. For **snipMate** paste the `vim` folder content on the `~/.vim/snippets/` or `~/vimfiles/snippets/` for **Windows**.
4. For **neosnippet** paste the `vim` folder content on your **neosnippet** snippets folder.

> **NOTE:* I recommend neosnippet to use the snippets! It give less bugs and works with snipMate snippets to. [UltiSnips] (https://github.com/SirVer/ultisnips) is good to but is in Python and not VimL so it sometimes fails on Windows. 

### Snippets
To use this snipets enter one of this shortcuts on a JavasScript file:

```shell
ngconfig
ngconstant
ngcontroller
ngdirective
ngfactory
ngmodule or ngm or nginit
ngservice
ngdoc
nginjec
```

## License

The MIT License

Copyright (c) 2010-2012 Google, Inc. http://angularjs.org

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

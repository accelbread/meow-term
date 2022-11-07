# meow-term

This package integrates [meow]'s input modes with term's input modes.

Term's char mode consumes all inputs, making it not integrate well with meow.
This package solves this by setting term to line mode while in meow normal
mode, and setting term to the actual desired of line/char mode while in meow
insert mode.

After installing this package, add the following to your init.el:
```elisp
(meow-term-enable)
```

[meow]: https://github.com/meow-edit/meow

# Doom Railscasts

The Railscasts theme ported to the Doom Emacs theming API

## How to install

Add this to `packages.el` in your `.doom.d` folder
``` emacs-lisp
(package! doom-railscasts
  :recipe (:host github :repo "thegeorgeous/doom-railscasts"))
```

Then add this to `config.el`

``` emacs-lisp
(load-theme `doom-railscasts)
```


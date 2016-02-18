# silkworm-theme
Light Emacs theme with low contrast colors.

Created with [ThemeCreator](https://github.com/mswift42/themecreator).

## Screenshots

Org-mode / Clojure:
![Screenshot](https://github.com/mswift42/silkworm-theme/raw/master/silkworm-emacs-orgclojure.png)

Python / Ruby:
![Screenshot](https://github.com/mswift42/silkworm-theme/raw/master/silkworm-emacs-pythonruby.png)

## Installation:

add the following lines to your init.el (only if you have not done so already):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("melpa" . "http://melpa.org/packages/")))
    (package-initialize)



This will add the gnu and melpa repos to your emacs setup.

To install the theme:

**M-x package-install** silkworm-theme


To use the silkworm theme when starting emacs, add this to your init.el:

    (load-theme 'silkworm)



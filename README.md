[![MELPA](https://melpa.org/packages/eros-badge.svg)](https://melpa.org/#/eros)
[![License GPL 3][badge-license]](http://www.gnu.org/licenses/gpl-3.0.txt)

# Eros

**E**valuation **R**esult **O**verlay**S** for Emacs Lisp.

![Overlay](doc/overlay.png)

## Installation

Install via [MELPA](https://melpa.org/#/).

For general information on installing Emacs packages, see the [Emacs Wiki](https://www.emacswiki.org/emacs/InstallingPackages).

## Setup

In your init file, add the following to activate `eros-mode` and see Emacs Lisp evaluation results as inline overlays.

```emacs-lisp
(eros-mode 1)
```

Use `M-x eros-mode` to turn the minor mode off, or call

```emacs-lisp
(eros-mode -1)
```

## Credits

The code is mostly taken from [CIDER](https://github.com/clojure-emacs/cider), and the idea came from [Artur Malabarba's blog](http://endlessparentheses.com/eval-result-overlays-in-emacs-lisp.html).


[badge-license]: https://img.shields.io/badge/license-GPL_3-green.svg

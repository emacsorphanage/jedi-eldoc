# This is obsolete module !! Please use emacs-jedi

*Features of this module are merged with [emacs-jedi](https://github.com/tkf/emacs-jedi).*


# Eldoc with emacs-jedi

![screenshot](https://github.com/syohex/emacs-jedi-eldoc/raw/master/image/jedi-eldoc-sample.png)


## Requirements
* [jedi](https://github.com/davidhalter/jedi)
* [emacs-jedi](https://github.com/tkf/emacs-jedi)


## Configuration

```` elisp
(require 'jedi)
(require 'jedi-eldoc)

;; change face as you like
(set-face-attribute 'jedi-eldoc:highlight-function-argument nil
                    :foreground "green")

(add-hook 'python-mode-hook 'jedi-eldoc-mode)
````

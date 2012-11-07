# Eldoc with emacs-jedi

![screenshot](https://github.com/syohex/emacs-jedi-eldoc/raw/master/image/jedi-eldoc-sample.png)


## Requirements
* [jedi](https://github.com/davidhalter/jedi)
* [emacs-jedi](https://github.com/tkf/emacs-jedi)


## Configuration

```` elisp
(require 'jedi)
(require 'jedi-eldoc)

(add-hook 'python-mode-hook 'jedi-eldoc-mode)
````

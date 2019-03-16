# What is move-text.el ?
Move current line or region.

## Installation
Clone or download this repository (path of the folder is the `<path-to-color-rg>` used below).

In your `~/.emacs`, add the following two lines:
```Elisp
(add-to-list 'load-path "<path-to-color-rg>") ; add color-rg to your load-path
(require 'move-text)
```

## Usage
Bind your favorite key to functions:

 | Function       | Description                      |
 | :--------      | :----                            |
 | move-text-up   | Move current line or region up   |
 | move-text-down | Move current line or region down |

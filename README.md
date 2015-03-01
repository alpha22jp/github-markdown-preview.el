# github-markdown-preview.el

Emacs lisp to preview markdowned text with browser using Github markdown render API.

## Requirements

* Emacs 23 or higher.
* Browser (Tested on Firefox for Linux).

## Installation

<kbd>M-x package-install [RET] github-markdown-preview [RET]</kbd>

## Configuration

Add the following lines to your Emacs setup file.

```init.el
(require 'github-markdown-preview)
(github-markdown-preview-setup)
```

## Usage

`M-x github-markdown-preview` during editing markdwoned text file.

## Known issues

* Need to reload window when the preview file is already opened on the browser (This problem may be only for Firefox, but I haven't tested any other browser).

## History

version 0.1.0

* Initial release

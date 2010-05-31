# mysnippets

These are snippets for the yasnippet plugin used with emacs.

# Installation

## Get yasnippet

Tested with [yasnippet 0.6.1c](http://code.google.com/p/yasnippet/downloads/detail?name=yasnippet-0.6.1c.tar.bz2).

But check out the documentation and the recent bundle on [yasnippet.googlecode.com](http://code.google.com/p/yasnippet/).

Follow their installation for yasnippet, if you haven't got it already.

For me it turned out, that a new version is awesome, because of the `yas/new-snippet` command, which helps you creating snippets and storing them to your `yas/root-directory`.

## Set your yas/root-directory

    ;; Develop and keep personal snippets under ~/.emacs.d/mysnippets
    (setq yas/root-directory "~/emacs.d/mysnippets")
    ;; Load the snippets
    (yas/load-directory yas/root-directory)

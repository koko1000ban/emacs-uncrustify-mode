uncrustify-mode
================

Overview
--------
 this mode is Minor mode to automatically [uncrustify](http://uncrustify.sourceforge.net/).
 
Installation
------------
 drop requirements and `uncrustify-mode.el` into a directory in your `load-path`. If you have `install-elisp` or `auto-install`, you also be able to install
`uncrustify-mode.el` like:

	;; install-elisp
    (install-elisp "https://raw.github.com/koko1000ban/emacs-uncrustify-mode/master/uncrustify-mode.el")

    ;; auto-install
    (auto-install-from-url "https://raw.github.com/koko1000ban/emacs-uncrustify-mode/master/uncrustify-mode.el")

And then enable uncrustify-mode on target mode like:

    ;; (require 'uncrustify-mode)
	;; (add-hook 'c-mode-common-hook 
	;;    '(lambda ()
	;;        (uncrustify-mode 1)))

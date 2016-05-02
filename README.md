An Emacs color theme imitating Evangelion Unit-01 

Download the file color-theme-eva01.el to the directory ~/.emacs.d/themes, then add the following to your Emacs init file, e.g. ~/.emacs:

(load-file "~/.emacs.d/color-theme-eva01.el")
(require 'color-theme)
(setq color-theme-is-global t)
(color-theme-initialize)
(color-theme-eva01)

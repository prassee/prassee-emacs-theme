# prassee-emacs-theme
A dark theme for Emacs based on Doom Theme (https://github.com/hlissner/emacs-doom-theme). 

This is a work in progress theme and will have more updates. Since Iam using this theme for myself, I hope can push updates frequently. 

#### Installation

Download the prassee-theme.el in ~/.emacs.d/themes folder and add the below code in init.el

    (add-to-list 'custom-theme-load-path "~/.emacs.d/themes")

    (load-theme 'prassee t)


#### Mode line config 
If you would like to have a mode-line to look like mentioned in the screenshot, install powerline and add the following code in you ```init.el``` file.

    
    (use-package spaceline	
    :init
    (progn
        (require 'spaceline-config)
        (setq powerline-default-separator 'slant)
        (setq spaceline-workspace-numbers-unicode t)
        (setq spaceline-separator-dir-left '(left . left))
        (setq spaceline-separator-dir-right '(right . right))
        (setq powerline-height 27)
        (spaceline-toggle-window-number-on)
        (spaceline-toggle-buffer-modified-on)
        (spaceline-toggle-major-mode-on)
        (spaceline-toggle-battery-on)
        (spaceline-toggle-hud-on)
        (spaceline-toggle-projectile-root-on)
        (spaceline-emacs-theme)))


### TODO

    - while transitioning from doom-theme, completely disabled bold need a work around 
    - include Ensime specific settings to make Scala code look beautiful
    

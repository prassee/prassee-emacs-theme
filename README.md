# prassee-emacs-theme
A dark theme for Emacs.
Since Iam using this theme for myself, I hope can push updates frequently. 

#### Installation

##### MELPA 

    ;; install from melpa 
    (use-package prassee-theme)
        
##### Manual

Download the prassee-theme.el in ~/.emacs.d/themes folder and add the below code in init.el

    (add-to-list 'custom-theme-load-path "~/.emacs.d/themes")

    (load-theme 'prassee t)

#### Changes 
- got rid of spaceline and customized the default mode-line
- added default cursor type 
- Used iosevka-term font for editor and modeline
- removed linum in org-mode
# prassee-emacs-theme
A dark theme for Emacs based on Doom Theme (https://github.com/hlissner/emacs-doom-theme). 

This is a work in progress theme and will have more updates. Since I am using this theme for myself, I hope I can push updates frequently. 

#### Installation

##### MELPA 

    ;; install from melpa 
    (use-package prassee-theme)
    
    
    
##### Manual

Download the prassee-theme.el in ~/.emacs.d/themes folder and add the below code in init.el

    (add-to-list 'custom-theme-load-path "~/.emacs.d/themes")

    (load-theme 'prassee t)

#### Screenshot

![ScreenShot](https://cloud.githubusercontent.com/assets/863188/24575040/c6e5dcb8-16b9-11e7-8cee-143ea02f4fef.png)

#### Changes 
- added default spaceline changes to get same look and feel as presented in screenshot
- added default cursor type 
- custom font and size for modeline 


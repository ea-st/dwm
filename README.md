East's dwm build
=================

[Pictures go here when I configure the setup]


Patches
-------
* [Swallow](https://dwm.suckless.org/patches/swallow/)
* [Shiftview](https://lists.suckless.org/dev/1104/7590.html)
 
Software "dependencies"
---------------------
* [dmenu](https://tools.suckless.org/dmenu/)
* [Alacritty](https://github.com/alacritty/alacritty)


Additional dependancies

* libxcb (required by swallow)
* Xlib-libxcb (required by swallow)
* xcb-res (required by swallow)

Installation
------------


    git clone https://github.com/ea-st/dwm;cd dwm

 ------------------------------------------------

    make install

Add ```exec dwm``` to your <kbd>.xinitrc</kbd> file.



QNA
---
>"What are the keybinds?"
>>keybinds are located in the file <kbd>keybinds</kbd>.

>"How do I change X and Y?"
>>Mainly in the file <kbd>config.def.h</kbd>.

>"Why is dependencies in air quotes?"
>>dwm is relatively simple to configure so the software i've set it up with is optionable.

Disclaimer
----------

This is made mainly for myself, and for the purpose of archival.

This is not a special configuration i think you should use, it's just the one i made for me.

Do not expect competence or a efficient configuration.

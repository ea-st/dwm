east's dwm build
=================

[pictures go here when I configure the setup]


patches
-------
* [swallow](https://dwm.suckless.org/patches/swallow/)
* [shiftview](https://lists.suckless.org/dev/1104/7590.html)
* [vanitygaps](https://dwm.suckless.org/patches/vanitygaps/)
 
Software "dependencies"
---------------------
* [dmenu](https://tools.suckless.org/dmenu/)
* [alacritty](https://github.com/alacritty/alacritty)


additional dependancies

* libxcb (required by swallow)
* Xlib-libxcb (required by swallow)
* xcb-res (required by swallow)

installation
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
>>dwm is relatively simple to configure so the software i've set it up with is optional.

Disclaimer
----------

This is made mainly for myself, and for the purpose of archival.

This is not a special configuration i think you should use, it's just the one i made for me.

Do not expect competence or a efficient configuration.

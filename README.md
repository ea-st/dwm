east's dwm build
=================

[pictures go here when I configure the setup]

The contiuned work on this config will be sparse as I'm not planning on using this long term. </br>
[Xorg](https://x.org/) is antiquated and moving forwards I plan on using [dwl](https://github.com/djpohly/dwl) or a alternative.
> "Why not switch now?" 

I only have one functioning computer, a terrible laptop (Dell G15) which does not enjoy playing nicely. </br>
I have never used [Wayland](https://wayland.freedesktop.org/) and to my knowledge it is unfriendly with nvidia graphics cards (like everything else).</br> I'd like to avoid the extra headache until I get a more permanent set-up.


patches
-------
* [swallow](https://dwm.suckless.org/patches/swallow/)
* [shiftview](https://lists.suckless.org/dev/1104/7590.html/)
* [vanitygaps](https://dwm.suckless.org/patches/vanitygaps/)
* [actualfullscreen](https://dwm.suckless.org/patches/actualfullscreen/)
* [sticky](https://dwm.suckless.org/patches/sticky/)
* [dwmblocks (wip not yet added)](https://github.com/ashish-yadav11/)


software "dependencies"
---------------------
* [dmenu](https://tools.suckless.org/dmenu/)
* [alacritty](https://github.com/alacritty/alacritty/)


additional dependancies
-----------------------

* [xorg](https://wiki.gentoo.org/wiki/Xorg/Guide/)


installation
------------

Heres a quick [tutorial](https://dwm.suckless.org/tutorial/) you should read if you've never used dwm before.


    git clone https://codeberg.org/east/dwm;cd dwm

 ------------------------------------------------

    make install


------
QNA
---
>"What are the keybinds?"
>>keybinds are located in the file <kbd>keybinds</kbd>.
 
>"Why is dependencies in air quotes?"
>>dwm is relatively simple to configure so the software i've set it up with is optional.

>"How do I change X and Y?"
>>Mainly in the file <kbd>config.def.h</kbd>.


disclaimer
----------

This is made mainly for myself, and for the purpose of archival.

This is not a special configuration i think you should use, it's just the one i made for me.

Do not expect competence or a efficient configuration.

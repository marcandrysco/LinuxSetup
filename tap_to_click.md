Tap to Click
============

Add the code below to the file `/etc/X11/xorg.conf.d/50-synaptics.conf`.

```
Section "InputClass"
        Identifier "touchpad catchall"
        Driver "synaptics"
        MatchIsTouchpad "on"
        Option "TapButton1" "1"
        Option "TapButton2" "3"
EndSection
```

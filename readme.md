# Responsive Bongo Cat layout for Lily58 :drum: :smile_cat:

I was looking for a cute bongocat animatoion for my Lily58 board. I have found several in the QMK repo but none to my liking and especially with via support.

I have finally found an implementation that worked correctly, so I have added VIA support to it.


Strongly inspired by this implementation:![lily58_bongocat](https://github.com/Rwarcards762/lily58_bongocat)

### Install the qmk toolbox

`brew install qmk-toolbox`

### Commands to flash

**For seapicros**

`make lily58:bongocat:flash CONVERT_TO=rp2040_ce`

You can also do

`qmk flash -c -kb lily58/rev1 -km domnantas CONVERT_TO=rp2040_ce`

### Create a new keycap

`qmk new-keymap -kb matteo-lily58`

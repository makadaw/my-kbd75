# My KBD 75 rev2 setup

This repo contains my keyboard setup and a small guide for myself about the process. 
This document will not answer all your question, also as me, as I'm not a QMK pro.

# Layout setup

For visual layout seetup, I used http://qmkeyboard.cn/. 
It already has preset for few keyboards.

To export and import of completed layout, these sites normally use JSON.
Just import it and make your changes.

All supported QMK keycodes can be founded here https://beta.docs.qmk.fm/features/keycodes_basic

You also can compile `.hex` files for your firmware.
This files will be used by QMK toolbox later.

# QMK Toolbox
[QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases) used for programming keyboard. 

Once you've installed the QMK Toolbox software and downloaded a `.hex` file with your keymap changes, you will need to flash your keyboard.

You will be able to set your keyboard to "Bootloader" mode with FN + backspace. Doing this, your keyboard will reconnect as a new device called `ATmega32u4`.

# My Layout

Current layout replicate default Apple keyboard ex: brightness control, music prev, play/stop, next, volume control.

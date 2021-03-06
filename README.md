# TouchscreenToggle
Scripts for computers with Wacom digitizers / touch screens to easily toggle touchscreen capabilities.    
For example: on multi-head setups with one touchscreen, or so you can use the digitizer as a drawing tablet for a second display. Also, you can use this with a single-monitor setup, to toggle the touchscreen on and off for tablets that lack palm rejection.

The `toggle` script asks you for the monitor you want to map the touch to. Simply select it.

If you have only one display, `toggle_single_screen` is for you. It turns on and off the touchscreen on your tablet.


### Usage:
0. Clone the repo and make sure dmenu, xinput, and xrandr are installed.
1. Make sure touch_device_name, wacom_eraser, and wacom_stylus are set correctly in `toggle`. If you have only one monitor, then you can use `toggle_single_screen`, you will need to simply set touch_device_name. 
*Check the output of `xinput list` to find out what your touch device is called. ThinkPad X220 tablet users, you can leave this at the default and it should work fine.*
2. Map the script to a button or keyboard shortcut in your DE / WM of choice. Press the button. Enjoy! :)

#### Bugs:
None yet. Open an issue if you find one, open a PR if you find one and want to help fix it. Thank you!
Check out my other projects on [my website](https://shantaram.xyz).

# TouchscreenToggle
A shell script for computers with Wacom digitizers / touch screens to easily toggle touchscreen mapping, for example on multi-head setups with one touchscreen, or so you can use the digitizer as a drawing tablet for a second display.

The default script cycles through these settings:
```
1. Touch and Wacom both mapped to internal display, touch enabled
2. Wacom mapped to internal display, touch disabled
3. Wacom and touch mapped to external display, touch enabled
```
### Usage:
0. Clone the repo.
1. Make sure ext_monitor and int_display, along with touch_device_name, wacom_eraser, and wacom_stylus are set correctly in `toggle`.
2. Map the script to a button or keyboard shortcut in your DE / WM of choice. Press the button.

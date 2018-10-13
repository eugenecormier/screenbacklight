This is my screen backlight script. This turns the screen backlight up/down. This was coded with my current window manager in mind, AwesomeWM. Simply bind the hotkeys to this script.

Invocation
---------------
Turn it up: screenbacklight +

Turn it down: screenbacklight -

Setup
---------------
Before running review the code and change the variables at the head of the file

'interface' is the path to your screen backlight /sys/class file

'steps' is how many levels you want between min and max brightness

'maxvalue' is the maximum value (0 is presumed to be the min)

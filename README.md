# PiClock
Raspberry Pi Modifications


Setting the clock to auto start
At this point the clock will only start when you manually start it, as described in the Run It section.
Use only one autostart method.

Autostart Method (Found to be the most successful)

cd /home/pi/PiClock && chmod +x PiClock.desktop && ln PiClock.desktop ~/Desktop && mkdir ~/.config/autostart && ln PiClock.desktop ~/.config/autostart

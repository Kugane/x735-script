# x735-script
This is the safe shutdown script for x735. It is identical to the x730 script except it has been updated to use the x735 name.

Press the momentary button or external momentary power switch to turn on
Press the momentary button or external momentary power switch and hold for 1~2seconds to reboot
Press the momentary button or external momentary power switch and hold for 3~7seconds to implement safe shutdown
Press the momentary button or external momentary power switch and hold for more than 8 seconds to force shutdown

How to install and setup the x735 script:

* step 1:
> wget https://raw.githubusercontent.com/FlyBoy6001/x735-script/master/x735.sh

> sudo chmod +x x735.sh

> sudo bash x735.sh

* step 2:

> printf "%s\\n" "alias x735off='sudo x735shutdown.sh'" >> ~/.bashrc

* step 3:
> sudo reboot

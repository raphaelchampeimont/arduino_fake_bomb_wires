# arduino_fake_bomb_wires
A prop bomb where you need to cut the right wires. This was used as part of an escape game we organized for our family.

See it in action in this YouTube video: https://www.youtube.com/watch?v=fAxLHOgLmgc

General idea: To "defuse" the "bomb", the players need to cut the right wires (so you need to solder new wires for every game). When the bomb is defused, it displays a secret code (which could for example allow to open a lock sealing the bomb or anything else in an escape game).

Features:
* 6 wires in which you have to cut the right ones
* Countdown to 0
* When no time is left, screen goes red and displays "BOOM"
* For each correct wire that is cut, an asterisk displays on the screen
* When all the correct wires are cut, timer stops, screen goes green and displays a secret code 
* As long as an incorect wire is cut, time goes down twice as fast and screen is red
* The bomb can still be defused if an incorrect wire has been cut, provided the wire is reconnected (you could provide players crocodile clips or even solder & iron)

You can power it the way you want, in my case I used a 9V battery (connected to Vin and GND).

## Schematic
![Schematic](fake_bomb_schematic.png?raw=true)

## Photos
Here is what is looks like:
![Photo of final result](final_result.jpg?raw=true)

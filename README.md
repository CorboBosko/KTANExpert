# KTANExpert
A Phython BombManual Expert for the game, **Keep Talking and Nobody Explodes**
It's not done yet. As of right now, it only does:
* Wires
* Button
* Keypad
* Simon Says
* Who's On First
* Memory
* Morse-Code

(For more information on modules, visit bombmanual.com)

# TO INSTALL:
Just place KTANExpert.py, who2lists.py, and morse.py into a folder, and run KTANExpert.py somehow.
*shrug*


# Module Instructions
## Morse-Code
Enter the morse code as it is flashed to you in the module. 
Use period( . ) and minus( - ) with a space between letters to input the morse (represented by a longer space in the flasing module.)
When the module stop flashing the longest and then starts again, it means the word is restarting. 
The program does NOT require that you start at the beginning of the word, only that you don't duplicate any letters already input.
Once you have the morse word input (with no duplication), press ENTER, and input the frequency provided.

### Example:
1. KTANE flashes: .. -.-. -.-   - .-. .. -.-. -.-   - .-. .. -.-. -.-   - .-. .. -.-. -.-   etc.
2. You input: **.. -.-. -.- - .-.** into the program and press ENTER
3. The Programs gives you: **Word was: Trick    Input 3.532 MHz**
4. You set the frequency to 3.532 MHz in KTANE. *Module Complete, move on to the next on.* 

## Complicated Wires
Going one wire at a time, answer the given questions with **y** for Yes and **n** for No. If you make a mistake, the function will be ended, and you will have to re-enter it at the Module Selector.
Once you have input the details, the Expert will give you a command. Use the following table to find out what you have to do to that wire:

| Command | Do to Wire |
| ------- | ---------- |
| Cut     | Cut that Wire |
| Do not Cut | Do not cut that wire, just move on |
| If 2 Battery, cut | Cut only if there are 2 or more batteries on the bomb |
| If Parallel port, cut | If there is a long parallel port on the bomb, cut that wire |
| If Serial even, cut | If the last digit of the serial number is even, cut that wire |

Once you have recieved a command, the Expert will ask if the wires are done. If not, answer **n**, and continue the module. If you are done, answer **y**, and you will be put back to the Module Selector. 

### Example:
1. KTANE gives you a red and blue twisted wire with an LED and no Star.
2. You enter **y** for Blue? Red? and LED?
3. You enter **n** for Star?
4. The Expert gives you **If Serial even, cut**
5. You check the Serial Number on the Bomb, its last number is 6
6. You cut that wire, and nothing happens
7. Repeat until module is done. 
8. Once the module is done, answer **y** to the loop question in the Expert. *Module Complete, move on to the next on.* 


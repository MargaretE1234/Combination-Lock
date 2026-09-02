
🔐 Combination Lock

This project is an Arduino-based combination lock that uses four push buttons and an RGB LED to simulate a simple electronic security system. Each button represents a letter in the combination, with A being the first button on the left, followed by B, C, and D.

The correct combination is BDCA. The Arduino keeps track of the order in which the buttons are pressed and compares the input to the programmed combination. If the correct sequence is entered, the RGB LED turns pink, indicating that the lock has been successfully opened.

If the wrong combination is entered, the system resets and requires the user to enter the sequence again. Each time an incorrect combination is entered, the RGB LED turns red to indicate an error. The same happens for each time the correct combination is entered, but the LED turns green. This happens till the combination is completely correct and the LED turns pink.

Components used:

Arduino Uno
4 push buttons
RGB LED
Resistors
Breadboard
Jumper wires


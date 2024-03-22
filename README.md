# Keylogger
Designed to work in the background unknown to the victim of this program

This program utlilizes the pynput API with the keyboard object. 

It works by defining a listener for the keyboard that calls the keyPressed function on any key press.

![image](https://github.com/JordanPenaloza/Keylogger/assets/113396128/e89a9ea9-eb5d-484d-9d69-f980118e2802)

In the keypressed function we print out the key that was passed and store it in keyfile.txt

Whenever the user pressed special keys like space or ctrl, the program crashes so we add an error handler to except it to not crash the program.

![image](https://github.com/JordanPenaloza/Keylogger/assets/113396128/f836fe3a-679b-488c-a849-283b0008a92e)

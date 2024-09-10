# Speed Typing Test

This project is a simple Speed Typing Test built using Python's curses module. The program tests your typing speed by displaying a random string of text that you need to type as quickly and accurately as possible. The Words Per Minute (WPM) score is calculated and displayed in real time.

## Features
Random text loading: Loads a random line of text from an external text.txt file.
WPM Calculation: Displays your typing speed in words per minute, updating as you type.
Typing Feedback: Shows real-time feedback for correctly or incorrectly typed characters.
Exit Option: Press ESC at any time to exit the program.
Simple UI: Built with Python's curses library for a terminal-based interface.

## Prerequisites
Ensure you have Python installed (preferably Python 3.x). You also need the curses module, which is included by default in most UNIX-based systems. However, it is not natively supported on Windows, so if you are using Windows, you may need to install the windows-curses package:
Ensure there is a text.txt file in the project directory. This file should contain lines of text from which the program will randomly choose.
Run the program:

## Usage
When you start the program, a welcome screen will appear. Press any key to begin.
A line of text will appear at the top of the screen. Type the text as accurately and quickly as possible.
Your WPM (words per minute) score will be updated as you type.
If you make a mistake, the character will be highlighted in red.
Press ESC at any time to exit the game.

## Controls
Type characters: Simply start typing the displayed text.
Backspace: Use Backspace to delete the last character.
ESC: Exit the program at any time by pressing ESC.

## Acknowledgements
This project was developed by Devashish Gupta.

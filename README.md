Simple Keylogger
This project is a Basic Keylogger written in Python that captures keystrokes and logs them to a file. The keylogger records every keystroke made by the user and saves it into a designated file for review.

Key Features
Captures and logs every keystroke typed on the keyboard.
Handles special keys (like space, enter, and tab) and converts them to readable format.
Stores the logs in a text file (key_log.txt).
Simple and easy-to-understand Python implementation.

How It Works
The keylogger listens for all keystrokes using the pynput library. As each key is pressed, the program logs the key to a file. Special keys like space, enter, and tab are formatted for readability in the log file.

Code Breakdown:
log_keystroke function:
This function captures each keystroke, processes it (removing unnecessary characters), and logs it to the file key_log.txt.
start_keylogger function:
This function starts the keylogger and listens for key presses, writing them to the log file continuously.
Requirements

You need the following dependencies to run this keylogger:

Python 3.X
pynput library

Install the required library:

pip install pynput

Usage
Clone the repository : git clone https://github.com/irfanahmd1/PRODIGY_CS_4.git

Run the script:

python keylogger.py

The keylogger will start running in the background and log all keystrokes to key_log.txt in the current directory.

Press Ctrl + C to stop the keylogger.

Example Output in key_log.txt:

Hello World!
This is a test keystroke log.

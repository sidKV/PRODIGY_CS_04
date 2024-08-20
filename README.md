# PRODIGY_CS_04

# Task-04
Create a basic keylogger program that records and logs keystrokes. Focus on logging the keys pressed and saving them to a file. Note: Ethical considerations and permissions are crucial for projects involving keyloggers

# Simple Keylogger
A simple keylogger is a software tool designed to monitor and record keystrokes typed on a keyboard. It captures each key pressed by the user and logs this data to a file or other storage medium. Keyloggers can handle various types of input, including regular keys, special keys (e.g., Enter, Space, Tab), and may also log timestamps. While keyloggers can be used for legitimate purposes such as parental control, employee monitoring (with consent), or debugging, they can also be misused to capture sensitive information without the user's consent. Therefore, their use is subject to strict ethical and legal considerations.

# How It Works:
on_press(key): This function is called whenever a key is pressed. It attempts to log the key to a file. For special keys (like space, enter, tab), it logs a readable representation.
on_release(key): This function checks if the esc key is pressed, and if so, stops the keylogger.
Log File: The keystrokes are saved in a file named keylog.txt.
Install Required Library: Ensure you have the pynput library installed.

# Repository Contents
PRODIGY_CS_04.py : The main Python script containing the implementation of the Simple Keylogger.
README.md : This file, providing an overview of the task and the project.

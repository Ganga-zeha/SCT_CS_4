SCT_CS_4 - Keylogger 

Task Objective:
Create a basic keylogger program that:
- Captures key presses
- Logs them into a file
- Runs silently in the background

This project is for educational use only. Never use keyloggers without proper permission or on someone else’s device.

Tech Used:
- Python
- `pynput` library for capturing key events

How It Works:
- Each key press is recorded
- Characters are written into `keylog.txt`
- Special keys like `Ctrl`, `Enter` appear as `[Key.ctrl_l]`, etc.

Instructions to Run

bash
pip install pynput
python keylogger.py

"Type anything in another window (like Notepad), then come back and press Ctrl + C to stop logging.
Check the keylog.txt file to see captured keys."

# 🛠️ Keylogger (Educational Purpose Only)

This is a **basic keylogger** built with Python. Keyloggers are programs designed to capture keyboard input. While they can be useful for personal productivity tracking or testing keyboard input in applications, they are often used for unethical purposes. **This project is intended strictly for educational and ethical research purposes.**

## 🔍 About

This keylogger records every keystroke and logs them into a file named `keylogger.txt`. Additionally, the contents of this file (i.e., the captured keystrokes) are sent to a predefined email address using Python's built-in `smtplib`.

> ⚠️ **Disclaimer**: Unauthorized use of keyloggers is illegal and unethical. Only run this code on machines you own or have explicit permission to test on.

## 📦 Features

- Logs all keyboard input into `keylogger.txt`
- Sends the captured keystrokes to a specified email address
- Exits cleanly when the `Esc` key is pressed
- Easily extendable to send logs at regular intervals (not implemented in this version)

## 🚀 Usage

1. Make sure you have Python installed.
2. Install the required Python module:

   ```bash
   pip install pynput
   ```

3. Run the keylogger:

   ```bash
   python keylogger.py
   ```

> 🛑 Press `Esc` to stop the keylogger.

## 🧰 Dependencies

- [`pynput`](https://pypi.org/project/pynput/) – For listening to keyboard events  
- `smtplib` and `ssl` – For sending emails (comes pre-installed with Python)

## 📌 Notes

- The script is **not compiled into an executable**, so it needs to be explicitly run using the Python interpreter.
- You may configure the email and interval logic to extend the functionality, such as sending periodic reports.

## 🧪 For Educational Use Only

This tool is intended to **learn how keystroke capturing works**, understand the risks, and promote awareness around digital security. Use responsibly.


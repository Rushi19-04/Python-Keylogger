# Simple Keylogger
This is a simple keylogger program that records all keystrokes and stores them in a file. It uses the Python `keyboard` library to capture keyboard events and logs them to a specified file. The keylogger operates in the background, capturing both normal and special keys.

## Features
- **Key Logging**: Captures keystrokes including normal keys, special keys (e.g., Shift, Ctrl), and control keys like Enter and Space.
- **Exit Condition**: The program can be stopped by pressing the combination `ESC + x`.
- **File Logging**: Logs are stored in a text file for later analysis.
- **Stealth Mode (Windows only)**: Hides the console window (optional) to run the keylogger in the background without being noticed.

## Prerequisites
- Python 3.x
- The `keyboard` library (installable via pip)

## Installation
### Step 1: Install Required Libraries

To install the required libraries, run the following command:

```bash
pip install keyboard
```

### Step 2: Download or Clone the Repository

Clone the repository or download the script directly to your system.

```bash
git clone https://github.com/Rushi19-04/PRODIGY_CS_04.git
```

### Step 3: Update File Path

In the script, update the `file_path` variable to specify the location where you want to save the key logs. You can change the path to a location of your choice.

```python
file_path = r"C:\path\to\your\desired\location\output.txt"
```

## Usage

### Step 1: Run the Script
Run the Python script with the following command:

```bash
python simple_keylogger.py
```

### Step 2: Key Logging
While the program is running, it will capture all keystrokes. For special keys, such as the **Enter**, **Space**, **Shift**, or **Ctrl**, the program will log them as `[ENTER]`, `[SPACE]`, and `[SHIFT]` respectively.

### Step 3: Stop the Keylogger
To stop the keylogger, press the combination `ESC + x`. This will safely exit the program and stop logging keys.

## Notes
- **Stealth Mode**: The script hides the console window on Windows to ensure that the program operates silently in the background. If you don't want this feature, you can comment out or remove the lines involving `ctypes.windll`.
- **File Path**: Make sure the file path where the keylogs are being saved is correct and accessible. You can specify any directory path where you have write permissions.
- **Use Responsibly**: This keylogger is meant for educational purposes only. Use it responsibly and ensure that you have proper consent from users if running this software in any environment.

## License
This project is licensed under the MIT License.


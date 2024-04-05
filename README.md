**Simple Python Keylogger**

This is a simple Python keylogger script that logs keystrokes and prints them out every 10 seconds. The keylogger listens for keyboard events using the `pynput` library and records the keystrokes. It also checks for specific keys such as space, enter, backspace, and tab to provide human-readable logs. Additionally, it checks for the "exit" keyword to stop logging.

### Usage:

1. **Installation:**
    - Make sure you have Python installed on your system.
    - Install the `pynput` library using pip:
        ```
        pip install pynput
        ```

2. **Running the Script:**
    - Run the script `keylogger.py`.
    - The keylogger will start monitoring keyboard input immediately.

3. **Stopping the Keylogger:**
    - To stop the keylogger, type "exit" into any input field being monitored.

### Output:

The output will be printed to the console every 10 seconds, showing the captured keystrokes. Optionally, you can customize the output to save it to a file or perform other actions as per your requirements.

### Output Image

![Output Image](https://github.com/GOVARDAN-N-A/Keylogger/blob/main/Keylogger_output.png?raw=true)


# Key-Logger
The Key Logger project aimed to develop a Python-based application capable of monitoring and recording keyboard input for authorized security and monitoring purposes. The primary objective was to capture keystrokes in real time, log them with accurate timestamps, and store the data securely for later analysis. This tool was designed to assist in identifying user behavior patterns or detecting unauthorized access attempts, all while adhering to legal and ethical standards.

The development process began with thorough research on keylogger functionalities, associated risks, and ethical considerations. The pynput library was selected for its efficiency in listening to keyboard events in real time. The core script was implemented to silently capture keystrokes and associate each input with a precise timestamp. For secure data handling, log files were stored in an encrypted or access-protected format to avoid misuse or unauthorized access.

To enhance usability, a basic user interface was developed, enabling authorized users to view, search, and export the recorded logs easily. The keylogger was configured to run in the background, ensuring it did not interfere with the user’s regular system experience. An optional feature to auto-start the application during system boot was also integrated, strictly for educational or testing environments.

Throughout the project, extensive testing and debugging were conducted on different systems to ensure consistent and stealthy performance. The result was a lightweight, efficient, and user-friendly keylogging tool tailored for ethical monitoring scenarios.

Key Features:

Real-time keystroke capture using pynput

Accurate timestamp logging for each key event

Secure log storage with encryption or restricted access

Minimal user interface for reviewing and exporting logs

Silent background operation

Auto-start option for boot-time execution (educational use only)


Skills Developed: Python programming, Cybersecurity fundamentals, Network behavior analysis, Ethical hacking practices, File handling, and GUI design.

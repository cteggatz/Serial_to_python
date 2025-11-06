# Intro
HELLO Felipe

This is some test code to help you get started with what I have because I realized I dumped a
lot of new stuff on you.

for starts I recommend installing a venv enviornment with the following packages:
    - pyserial

I also recommend installing Arduino IDE and installing the ESP32 packages using this guide:
    - https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/

just run the code in the venv envirnment and try pointing the COM port to the port of the arduino.

# Logic
This is the exact logic that I have put on the ROS2 node.
Basically it is:
    1) reading the byte data via serial
    2) converting that data into usable python values and making sure it is valid data
    3) returning said valid data

The logic works here, we just now need to put it into an environment where we can actually test it!

I would recommend:
    1) understanding what I wrote and editing it. It aint perfect :(....
    2) working with Devansh to set up the 2025 / 2026 Repository on the base station / rover
        so we can actually test our code!

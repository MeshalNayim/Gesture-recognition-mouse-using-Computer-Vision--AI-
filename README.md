## Hand Gesture mouse Control System using openCV and mediapipe

Overview
This project leverages hand gesture recognition to control various system functions using Python. By tracking hand movements and finger positions through a webcam, users can perform actions such as adjusting volume, scrolling, and switching between windows. The system utilizes the OpenCV library for computer vision tasks, PyAutoGUI for automation, and the Pycaw library to control audio settings.

Features
Volume Control: Adjust system volume by changing the distance between the index finger and thumb.
Mouse Movement: Move the mouse cursor based on the position of the index finger.
Clicking: Perform mouse clicks with a pinch gesture (index and middle fingers up).
Scrolling: Scroll up or down with specific hand gestures.
Window Management: Switch between windows using a four-finger gesture.
Pause/Play: Tap the space bar using a thumb and pinky gesture.

Requirements
Python 3.8 or higher
OpenCV
NumPy
PyAutoGUI
Pycaw
HandTrackingModule (Custom module for hand tracking)
opencv-python
numpy
pyautogui
pycaw



Gestures:

Volume Control: Spread the index finger and thumb; adjust the volume by changing the distance between them.
Mouse Movement: Move the index finger to control the mouse cursor.
Clicking: Pinch with the index and middle fingers to click.
Scrolling Down: Spread three fingers and keep them above the middle of the screen.
Scrolling Up: Place the pointer and pinky fingers down while keeping the middle and ring fingers up.
Window Management: Extend all fingers except the thumb to switch between windows.
Pause/Play: Tap the space bar by extending the thumb and pinky fingers while keeping the other fingers down.

Demo:


Volume Control: Show how the volume bar reacts to hand gestures.
Mouse Movement: Demonstrate cursor movement with index finger positioning.
Clicking Gesture: Visualize the clicking action triggered by a pinch gesture.
Scrolling: Illustrate controlled scrolling actions with three-finger gestures.
Window Management: Display the tab view triggered by a four-finger gesture.
Pause/Play Action: Show the space bar action using thumb and pinky fingers.

Contributing
Feel free to submit pull requests, report issues, or suggest improvements. Contributions are welcome!

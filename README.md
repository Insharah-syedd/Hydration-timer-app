# Hydration-timer-app
A simple hydration timer app to track water intake and send reminders.
Hydration Timer App
A desktop hydration reminder built with Python and Tkinter. The app encourages you to drink water regularly by running a timer and tracking your progress visually.

Features
Graphical user interface (GUI) using Tkinter
10-minute countdown timer (default, can be changed in code)
Visual water glass indicator updates as time passes
Tracks number of glasses of water consumed
Plays a sound alarm when time is up (requires alarm.mp3)
Notification popup when it's time to drink
Start, pause/resume, and reset controls
Getting Started
Make sure Python 3 is installed.
Install required packages:
pip install pillow pygame
Place water glass images in the images/ folder and an alarm.mp3 sound file in the project directory.
Run the timer:
python timer.py
Usage
Click START to begin the timer.
When the timer reaches zero, a sound will play and a popup will remind you to drink water.
Click RESET to restart the timer.
The app tracks how many glasses you've had today.
Project Structure
day2/
  README.md
  timer.py
  images/
    full.png
    full1.png
    ...
    full6.png
 alarm.mp3

 author
 INSHARAH SYED

# Motion Detection Alarm

This project implements a motion detection alarm system using Python and OpenCV. It starts monitoring the webcam when it is activated and sounds an alarm when motion is detected. It also sends an email notification to the user when motion is detected with few images of the motion. The user can adjust the motion detection sensitivity and the email notification settings.

## Features

- Real-time motion detection using computer vision techniques
- Adjustable motion detection sensitivity
- Emergency alarm when motion is detected
- Send email notification when motion is detected with few images of the motion
- Simple and intuitive user interface

## Requirements

- Python 3.x
- OpenCV
- NumPy
- imutils
- winsound (for Windows users)
- Mail (custom module for sending emails)

## Installation

1. Clone the repository

   ```
   git clone https://github.com/ezhil56x/Motion-Detection-Alarm-OpenCV.git
   ```

2. Install the dependencies

   ```
   pip install opencv-python numpy imutils
   ```

3. Configure the email settings in `mail.py`

   ```
   sender_email = "your_email_address"
   sender_password = "your_email_password"
   recipient_email = "recipient_email_address"
   ```

4. Run the application

   ```
   python main.py
   ```

5. A window will appear with the webcam feed. Press 't' to activate/deactivate the motion detection alarm. Press 'q' to quit the application.

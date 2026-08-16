# face-rec-attendance-sysytem-Project Summary

Face Recognition Attendance Management System is a Python-based desktop application that automates attendance using facial recognition and computer vision. The system captures a user’s facial images through a webcam, detects faces using the Haar Cascade classifier, and trains an LBPH (Local Binary Pattern Histogram) face recognition model to identify registered users.

The application provides a Tkinter GUI with modules for user registration, image capture, model training, automatic attendance, manual attendance, and attendance viewing. Once a registered face is recognized, the system automatically records the user's enrollment number, name, date, and time in CSV files, while attendance reports can be viewed in tabular format.

Technologies Used
Python
OpenCV
LBPH Face Recognition
Haar Cascade
Tkinter
NumPy
Pandas
Pillow
CSV
pyttsx3 for voice notifications
Main Modules
User Registration – Collects enrollment number and name.
Face Image Capture – Captures multiple facial images through the webcam.
Model Training – Trains the LBPH face recognition model using the collected images.
Automatic Attendance – Recognizes registered users and records attendance.
Manual Attendance – Allows attendance to be entered manually when required.
Attendance Reports – Generates and displays attendance records and percentages.

# face-recognition-attendance-system
The Face Recognition Attendance System is a Python-based project that utilizes face recognition techniques to automate the attendance process. It provides an efficient and convenient way of marking attendance by recognizing and verifying faces of individuals. 

## Features

- Face detection and recognition: The system detects faces in images or video streams and recognizes them by comparing them with known faces in the database.
- Attendance logging: It maintains a log of attendance records, including the date, time, and individual's name or identifier.
- Real-time processing: The system can perform face recognition in real-time, making it suitable for live attendance management.
- User-friendly interface: It provides a simple and intuitive interface to interact with the system, allowing users to easily enroll new faces, update the database, and view attendance records.

## Technology used
- The main technology used in the project is computer vision, using openCV. The code connects the data of all users through a backend api, saves it in a folder and everytime a user in the database gives their attendance, it is updated in the backend api.

## Usage
- Launch the application by running main.py.
- Use the provided user interface to perform various tasks such as enrolling new faces, updating the face database, and viewing attendance records.
- The system will continuously monitor the camera or specified image/video source for faces. When a face is detected, it will compare it with known faces in the database and mark attendance if a match is found.
- Attendance records will be logged in the specified file, including the date, time, and the name or identifier of the individual.

## Future Scope

-As this code is developed, new features will be added, The main one being authenticity in face recognition. This application will bw connected with an OxyMeter
made with IoT technology, which will authenticate the user being present in real time by reading their fingerprint and displaying their oxygen level.


This project is done and is in use in **IoT lab. KIIT**

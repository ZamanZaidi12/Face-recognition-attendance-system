# Face-recognition-attendance-system
Attendance Management System based on Face Recognition using Python  and OpenCv  
Face recognition-based attendance systems utilize sophisticated algorithms and computer vision techniques to identify and authenticate individuals based on their unique facial features. By capturing and analyzing facial patterns, these systems can accurately determine an individual's presence, eliminating the need for manual attendance registers, ID cards, or biometric devices.

# Features:

Face Detection: Utilizes a pre-trained deep learning model to detect faces within images or video streams.
Face Recognition: Uses facial feature extraction and comparison algorithms to recognize individuals from their facial features.
Real-time Processing: Performs face detection and recognition in real-time, allowing for immediate attendance marking.
Attendance Logging: Records attendance data, including date, time, and the recognized individuals, in a structured database.
User-friendly Interface: Provides a simple and intuitive interface for users to interact with the system, view attendance reports, and manage settings.
Customization: Allows administrators to add new individuals, update existing profiles, and manage the database.
Security and Privacy: Implements appropriate security measures to protect sensitive facial data and adheres to privacy regulations.
Notifications: Notifies administrators or individuals about successful attendance marking or any system issues.

### Technologies Used or Requirements:
- Programming Language: Python
- Libraries: OpenCV, dlib, face_recognition, SQLite (for database management)
- User Interface: Tkinter (for GUI)
- Version Control: Git (for project versioning and GitHub hosting)
- Opencv(`pip install opencv-python`)
- Tkinter(Available in python)
- PIL (`pip install Pillow`)
- Pandas(`pip install pandas`)

### What steps you have to follow??
- Download my Repository 
- Create a `TrainingImage` folder in a project.
- Open a `AMS_Run.py` and change the all paths with your system path
- Run `AMS_Run.py`.

### Project Structure

- After run you need to give your face data to system so enter your ID and name in box than click on `Take Images` button.
- It will collect 200 images of your faces, it save a images in `TrainingImage` folder
- After that we need to train a model(for train a model click on `Train Image` button.
- It will take 5-10 minutes for training(for 10 person data).
- After training click on `Automatic Attendance` ,it can fill attendance by your face using our trained model (model will save in `TrainingImageLabel` )
- it will create `.csv` file of attendance according to time & subject.
- You can store data in database (install wampserver),change the DB name according to your in `AMS_Run.py`.
- `Manually Fill Attendance` Button in UI is for fill a manually attendance (without facce recognition),it's also create a `.csv` and store in a database.

### Screenshots
<img src="https://github.com/ZamanZaidi12/Face-recognition-attendance-system/blob/main/Screenshot%20(101).png">
<img src = "https://github.com/ZamanZaidi12/Face-recognition-attendance-system/blob/main/Screenshot%20(104).png">
<img src ="https://github.com/ZamanZaidi12/Face-recognition-attendance-system/blob/main/Screenshot%20(106).png">
<img src ="https://github.com/ZamanZaidi12/Face-recognition-attendance-system/blob/main/Screenshot%20(155).png">


### Notes
- Ensure you have the necessary hardware (webcam or camera module) to capture images or video streams for recognition.
- Respect privacy and legal regulations when using facial recognition technology.
- It will require high processing power(Upto 4 GB RAM)

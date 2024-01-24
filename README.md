# Face Recognition based Attendance System
## Overview
This Python-based Face Recognition Attendance System combines OpenCV, Flask, NumPy, and Pandas to provide accurate identification and efficient attendance tracking. The system's modular structure allows for seamless deployment and user-friendly management.
## Features
- **Face Recognition:** Utilizes OpenCV for precise identification, ensuring accuracy in attendance tracking.
- **User-Friendly Interface:** Implemented with Flask to facilitate easy deployment and efficient day-to-day management.
- **Data Handling:** Optimal data management using NumPy and Pandas, enhancing the system's effectiveness in tracking attendance records.
## Installation

1. Clone the repository to your local machine.
   ```
   https://github.com/nishantranjan127/face_recognition_attendance.git
   ```
2. Install the required packages using
   ```
   pip install -r requirements.txt
   ```
3. Download the dlib models from https://drive.google.com/drive/folders/12It2jeNQOxwStBxtagL1vvIJokoz-DL4?usp=sharing and place the data folder inside the repo

## Usage

1. Collect the Faces Dataset by running ``` python get_faces_from_camera_tkinter.py``` .
2. Convert the dataset into ```python features_extraction_to_csv.py```.
3. To take the attendance run ```python attendance_taker.py``` .
4. Check the Database by ```python app.py```.

## Libraries Used
Here's a breakdown of what each library/module is typically used for:
1. **dlib:** A toolkit for machine learning and computer vision. In this context, it's likely used for face detection and facial landmarks.
2. **numpy:** A library for numerical operations. It's commonly used for handling numerical arrays, which is helpful for manipulating image data in the context of face recognition.
3. **cv2 (OpenCV):** An open-source computer vision library. It's used for image processing tasks, and in this case, likely for tasks like reading and displaying images, and potentially for some face recognition functionalities.
4. **os:** A module for interacting with the operating system. It can be used for tasks like file and directory operations.
5. **pandas:** A data manipulation and analysis library. It's useful for handling and processing structured data, which could be relevant for managing attendance records.
6. **logging:** A module for flexible event logging. It's used for recording events in your application, which can be valuable for debugging and monitoring.
7. **sqlite3:** A module for interacting with SQLite databases. It's likely used for storing and managing data related to attendance.
8. **datetime:** A module for working with dates and times. It's useful for handling timestamps, which could be relevant for recording attendance times.
## Folders Structure
1. **app.py:** Main application file where your face recognition attendance system logic is likely implemented.
2. **attendance.db:** SQLite database file, probably used for storing attendance-related data.
3. **attendance_taker.py:** File responsible for taking attendance, interacting with the face recognition system, and updating the database.
4. **features_extraction_to_csv.py:** File that might handle the extraction of facial features and store them in a CSV file, essential for face recognition.
5. **get_faces_from_camera_tkinter.py:** A file that seems to be related to capturing faces from a camera using Tkinter, possibly for initial data collection.
6. **requirements.txt:** A file specifying the dependencies and their versions required for your project. Useful for others to set up the same environment.
7. **README.md:** A placeholder for the project's documentation. It's usually a good practice to fill this with information on how to set up and use your project.   
8. **LICENSE:** A file that likely contains the license information for your project.
9. **.gitignore:** A Git configuration file that specifies which files and directories should be ignored when versioning your project with Git.
10. **.gitattributes:** Another Git configuration file that defines attributes for paths in your project.


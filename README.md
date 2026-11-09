**FaceMark – Face Recognition Based Attendance System**

A Python-based attendance management system that uses face recognition technology to automatically identify individuals and record their attendance. The project was independently developed, and I am actively working on new projects to expand and improve this system.

🧠 **Overview**

The system captures real-time video from a webcam, detects faces, recognizes them by comparing with stored images, and marks attendance automatically with date and time. Attendance records are stored in CSV files, eliminating the need for manual attendance methods.

🎯 **Objectives**

1. Automate attendance using face recognition
2. Reduce manual effort and human error
3. Provide a simple and effective attendance solution for classrooms or labs

📂 **Project Structure**

1. face recognise.py – Core face detection and recognition logic
2. UI.py – Graphical user interface to run the system
3. Attendance CSV files – Stores attendance records
4. Image files (.jpg/.png) – Known face images used for recognition

🛠️ **Technologies Used**

1. Python 3
2. OpenCV – Image and video processing
3. Dlib / face_recognition – Face detection and encoding
4. NumPy – Numerical operations
5. CSV / Pandas – Attendance storage and handling

**Note**: NLP is not used in this project.

✨ **Features**

1. Real-time face detection using webcam
2. Face recognition with stored images
3. Automatic attendance marking with timestamp
4. CSV-based attendance record generation
5. Prevents duplicate attendance in a single session

📦 **Installation**

Clone the repository:

 git clone https://github.com/HimJaiss/FaceMark.git
 cd FaceMask

**Install required dependencies:**

pip install opencv-python dlib face_recognition numpy pandas


🚀 **How to Run**

1. Add images of known persons to the project directory
2. Image file names should match the person’s name
3. Run the application:

**python UI.py** or **python "face recognise.py"**

The webcam will open and attendance will be marked automatically.

📊 **Attendance Output**

Attendance is saved in CSV format with date and time:

    Name	       Date	      Time
1. Himanshu	  2025-02-10	10:15:22
2. Raushan	  2025-02-10	10:18:05

🧠 **Working Principle**

1. Capture frames from webcam
2. Detect faces in each frame
3. Encode and compare faces with known encodings
4. Mark attendance for recognized faces
5. Store data in CSV file

🔮 **Future Enhancements**

1. Database integration (MySQL)
2. Web-based interface using Flask
3. Improved accuracy and speed
4. Liveness detection to prevent spoofing
5. Detailed attendance reports

⚠️ **License**

This project does not currently have a license and is intended for academic and learning purposes only.

Single Attendance System (Face Recognition)

This project is a face recognition–based attendance system that I developed to automate the traditional attendance process. Instead of marking attendance manually, the system uses a webcam to detect and recognize faces in real time.

I built this project using Python and OpenCV, focusing on applying computer vision concepts to a real-world problem.

The system ensures that attendance is recorded only once per person, making it efficient and reducing duplicate entries.

🚀 Key Highlights
Real-time face detection and recognition
Automated attendance marking with timestamp
Duplicate entry prevention logic
Lightweight and efficient implementation
Structured CSV-based data storage
🧠 What I Learned

While building this project, I gained practical experience in:

Face detection and image processing using OpenCV
Working with real-time video streams
Data handling using Pandas
Writing clean and modular Python code
Debugging and optimizing performance
🛠️ Tech Stack
Python
OpenCV
NumPy
Pandas
📂 Project Structure
Single_Attendance_System/
│── main.py              # Main program
│── attendance.csv       # Stores attendance records
│── images/              # Dataset of known faces
│── README.md
⚙️ How to Run
Clone the repository:
git clone https://github.com/your-username/single-attendance-system.git
Navigate to the project folder:
cd single-attendance-system
Install dependencies:
pip install opencv-python numpy pandas
Run the project:
python main.py
⚡ How It Works (Simple Flow)
Load images of known people
Encode facial features
Start webcam and capture frames
Detect and compare faces
If matched:
Record name
Add timestamp
Prevent duplicate entry
🎯 Real-World Applications
College attendance automation
Office employee tracking
Entry management systems
🔒 Limitations
Accuracy depends on lighting conditions
Works best with clear front-face images
Basic implementation (not deep learning–based)
🔮 Future Improvements
Integrate deep learning models (FaceNet / Dlib)
Add GUI interface
Store data in cloud/database
Deploy as a web or mobile application
📌 About This Project

This project is part of my learning journey in computer vision and real-time systems, where I focused on building something practical and scalable from scratch.

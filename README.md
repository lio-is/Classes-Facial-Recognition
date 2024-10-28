# Classes Facial Recognition Attendance App

Done by : Kamous Yahya
          Dec 2022
1. Overview
The Classes Facial Recognition Attendance App is a smart attendance management system that uses facial recognition technology to automate the process of taking attendance. It allows users to register their faces and mark attendance seamlessly.

2. Features
- Facial Recognition: Automatically recognizes registered users' faces using advanced algorithms.
- Attendance Tracking: Maintains a record of attendance for each user.
- User Registration: Easy registration process for new users with facial capture.
- Real-time Monitoring: Live monitoring of attendance with instant notifications.
- Data Export: Ability to export attendance data to various formats (e.g., CSV, Excel).

3. Technologies Used
- Programming Languages: Python, HTML, CSS, JavaScript
- Frameworks: Flask (for the backend), OpenCV (for facial recognition)
- Database: SQLite (or any other database of your choice)
- Libraries: NumPy, Pandas, Matplotlib

## Installation

Prerequisites
- Python 3.x
- Pip (Python package installer)
- OpenCV
- Flask

Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/lio-is/Facial-Recognition-Attendance.git
   cd Facial-Recognition-Attendance
Install Dependencies

bash
Copy code
pip install -r requirements.txt
Set Up Database

Create the database by running the setup script (if applicable).
bash
Copy code
python setup_database.py
Run the Application

bash
Copy code
python app.py
Open your web browser and navigate to http://localhost:5000.
Usage
User Registration:

Navigate to the registration page.
Upload a photo or capture your face using your webcam.
Your face will be stored for future recognition.
Marking Attendance:

Navigate to the attendance page.
Click on the "Mark Attendance" button.
The application will recognize your face and mark your attendance.
Viewing Attendance Records:

Admins can view attendance records by navigating to the admin panel.
Contributing
Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a pull request.

 

 


# License
This project is licensed under the MIT License - see the LICENSE file for details.

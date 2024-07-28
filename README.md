# Networked QR Code Attendance with Submission Window
This project is developed for Jain College of Engineering and Technology, Hubballi. It is a Django-based web application that facilitates attendance tracking using QR codes. The system includes distinct views for Faculty and Students. Students can mark their attendance by scanning a QR code, and this data is displayed and managed in the Faculty view. Additionally, the faculty can export attendance logs to CSV and XLS formats.

# Features
- QR Code Generation and Scanning: Students mark attendance by scanning a QR code displayed on the Faculty view.
- Attendance Logging: Attendance records are stored and can be viewed by faculty members.
- Data Export: Attendance logs can be exported to CSV and XLS formats by the faculty.
- Submission Window: Set a specific time window during which students can submit their attendance.
- Separate Views: Distinct views and functionalities for Faculty and Students.
- Homepage: Faculty view acts as the default homepage displaying the QR code for attendance.

# Requirements
- Python 3.x
- Django 3.x or higher
- Pillow
- qrcode
- pandas

# Installation
- Clone the repository:
git clone https://github.com/your-username/Networked-QR-Code-Attendance-with-Submission-Window.git
cd Networked-QR-Code-Attendance-with-Submission-Window

- Install dependencies:
pip install -r requirements.txt

- Apply migrations:
python manage.py migrate

- Run the development server:
python manage.py runserver

- Access the application:
Open your browser and go to http://127.0.0.1:8000/

# Usage
- Faculty View
Login as a faculty member.
The default homepage will display the QR code for students to scan.
View and manage attendance logs.
Export attendance data to CSV or XLS formats.
- Student View
Login as a student.
Scan the QR code displayed by the faculty to mark attendance within the specified submission window.

# Configuration
- Setting the Submission Window
You can configure the time window for attendance submission in the Django admin panel. This ensures students can only mark attendance during this predefined period.

- Customizing QR Code
The QR code can be customized by modifying the relevant views and templates in the Django application.

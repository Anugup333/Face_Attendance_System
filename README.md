INTRODUCTION: 

A Flask-based web application for automatic face recognition-based attendance marking, complete with a login system (Admin & Users), real-time camera feed, face registration, date-wise reports, and CSV/Excel export. Built using OpenCV, face_recognition, and Flask, this system is ideal for classroom or workplace attendance tracking.

PURPOSE:

The primary purpose of this project is to automate and secure the process of attendance marking using facial recognition technology. Traditional attendance methods (manual entry, RFID cards, biometric scanners) are time-consuming, prone to proxy attendance, or expensive to maintain. This system aims to address those challenges by leveraging computer vision and machine learning in a simple web-based interface.



Features:

✅ Login System (Users with session-based authentication)

✅ Face Registration (Add new users by capturing their face data)

✅ Real-Time Face Recognition for attendance

✅ Dashboard with Attendance Reports

✅ Export Attendance Data (CSV/Excel)

✅ Date-wise Filtering

✅ Modern Web Interface using HTML, CSS (Tailwind), and JavaScript


 TOOLS USED

1.  Backend	 :            Flask (Python 3.10 )
2.  Frontend :            HTML , Tailwind CSS , JS
3.  Face Recognition : 	  OpenCV, face_recognition , pickle
4.  Database :	          SQLite
5.  Export Support :	  CSV

How It Works

1. Admin Registers faces through the webcam.
2. The system encodes facial features and stores them.
3. On attendance page, the camera matches faces in real-time using face_recognition.
4. If matched, attendance is marked and saved to the database.
5. Admin can view/download attendance by date.

Screenshots :

Dashboard :  

![Screenshot 2025-05-15 131300](https://github.com/user-attachments/assets/29037e57-1064-41f9-bc81-1cee752b9423)

Face Registration :

![Screenshot 2025-05-15 131425](https://github.com/user-attachments/assets/c3eb2e43-2676-467f-b572-44feaa07c2e6)

Mark Attendance :

![Screenshot 2025-05-15 131501](https://github.com/user-attachments/assets/454d4f70-a0ac-41ea-86d0-faff56ddb88d)

Export CSV File for Record :

![Screenshot 2025-05-15 131907](https://github.com/user-attachments/assets/c3605b8b-7b56-47c2-979e-a644edada224)

![image](https://github.com/user-attachments/assets/3cd7866d-968a-494c-8a19-dbd45be14899)

View Attendance : 

![Screenshot 2025-05-15 131907](https://github.com/user-attachments/assets/c3605b8b-7b56-47c2-979e-a644edada224)

![Screenshot 2025-05-15 131950](https://github.com/user-attachments/assets/424a6184-56ce-4a21-878d-073573a46eee)


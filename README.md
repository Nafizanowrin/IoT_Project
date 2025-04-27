# Automatic Attendance System using IoT and ML

A smart attendance system that automatically marks student attendance using IoT and Machine Learning.
Live images are captured via an ESP-32 CAM module, processed through facial recognition, and attendance is recorded automatically in real-time.

---

## Project Structure

```
IoT_Project/
├── sensors/
│   ├── camera_capture.py          # Captures live images using ESP-32 CAM
│   ├── face_preprocessing.py      # Preprocesses images for better recognition
│   └── motion_detector.py         # Detects motion (optional for capture triggers)
├── controllers/
│   └── attendance_controller.py   # Controls attendance marking logic
├── data/
│   └── excel_api.py                # API for Google Sheets or Excel data integration
├── web_interface/
│   ├── app_server.py               # Hosts live feed and controls via browser
│   ├── add_student.py              # Enrolls new students from web UI
│   └── static/                     # Web assets (HTML, CSS, JS)
├── email_alert/
│   └── send_alert.py               # Sends email alerts for absentees
├── main.py                         # Main script to start the system
└── README.md                       # Project overview and documentation
                      # Project overview and documentation
```
---

## Features

   -  Live face detection using ESP-32 CAM.

   - Automatic attendance marking using facial recognition.

   -  Real-time attendance storage in Google Sheets.

   - Email alerts for students with multiple consecutive absences.

   -  Web-based dashboard for monitoring and manual controls.

   - Dynamic student enrollment without redeploying code.
---

## Technologies Used

   - ESP-32 CAM Module for image capturing

   - Python for backend and facial recognition

   - facial recognition libraries(face_recognation library in python )

   - Flask (or basic Python HTTP server) for web interface

   - Excel Sheets for data storage

   - SMTP (Simple Mail Transfer Protocol) for email alerts

   - JavaScript + HTML/CSS for frontend browser control

--- 

## Contribution

Pull Requests are welcome! If you find any issues or improvements, feel free to fork this repo and make a Pull Request.

Steps:

1. Fork this repository.
2. Clone your forked repository.
3. Create a new branch.
4. Commit your changes.
5. Push to your fork.
6. Open a Pull Request!

---

## Acknowledgements

This project was completed as part of an academic course under the supervision of my class teacher.  
Special thanks to all open-source contributors and the dataset providers.

---

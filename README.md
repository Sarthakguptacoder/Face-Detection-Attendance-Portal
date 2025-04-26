ATTENDANCE PORTAL USING FACE DETECTION 
This is a Python-based Attendance System integrated with Face Recognition, built to automate the process of marking attendance. It utilizes the OpenCV library for face recognition and Tkinter for the graphical user interface (GUI), making it both user-friendly and efficient. The system is designed for educational institutions or any organization requiring automated attendance tracking.

Features

- **Interactive GUI**: The application comes with an easy-to-use graphical interface created with Tkinter.
- **Face Recognition**: Uses OpenCV's LBPH face recognizer to detect and recognize faces for attendance.
- **Password Protection**: Ensures that new student registrations are protected with a password.
- **Dynamic CSV Handling**: 
  - Generates and updates a CSV file for student registration details.
  - Creates a new CSV file for each day to log attendance with accurate date and time.
- **Live Attendance Updates**: Displays the real-time attendance status for the day, showing student ID, name, date, and time.
  
Technologies Used

- **Tkinter**: For building the GUI.
- **OpenCV (cv2)**: For face detection and recognition using LBPH (Local Binary Patterns Histograms) face recognizer.
- **Pandas, Numpy**: For managing data and handling CSV operations.
- **Datetime**: For logging time and date for attendance.

   Once the program is running, a window will appear with options to register new students, view the current attendance, and more.

## How It Works

1. **Registration**:
   - Register new students by entering their details and capturing their face image.
   - A password is required to ensure secure registration.
   
2. **Face Recognition**:
   - When the student enters the system, their face will be captured, and the system will attempt to recognize the student based on pre-recorded facial data.
   
3. **Attendance Logging**:
   - Upon successful recognition, the student's attendance is marked for the day with the exact time and date.
   - A daily CSV file is updated with the recorded attendance.

4. **Attendance Report**:
   - The main screen will show live updates of the attendance for the current day in a tabular format.

Contributing

Feel free to fork the project, make changes, and create pull requests. If you find any bugs or have suggestions for improvements, feel free to open an issue.

 Contact Information

  - Sarthak Gupta 
  - University: VIT Bhopal University  
  -*Email: [sarthakgupta.sg2016@gmail.com]

---

Let me know if you'd like to make any adjustments!

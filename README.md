# Attendance System Using Face Recognition

This project is an **Attendance Management System** built using Python and OpenCV. It leverages **face recognition technology** to mark attendance automatically, eliminating manual processes and ensuring greater accuracy and convenience.

---

## Features

- **Face Detection**: Real-time face detection using OpenCV.
- **Face Recognition**: Identifies registered faces and matches them against a database.
- **Attendance Logging**: Automatically logs attendance for recognized individuals.
- **CSV Export**: Saves attendance records in a CSV file for easy tracking and analysis.
- **User-Friendly Interface**: Provides a simple interface for registering new faces and marking attendance.

---

## Prerequisites

Before running the project, ensure the following are installed:

1. **Python 3.6+**
2. **Required Libraries**:
   - OpenCV
   - NumPy
   - dlib (for face encoding)
   - face_recognition
   - pandas

Install the required libraries using:

```bash
pip install opencv-python numpy dlib face-recognition pandas
```

---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/SaloniSidheshwar31/pythonproject.git
```

2. Navigate to the project directory:

```bash
cd pythonproject
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## How It Works

1. **Face Registration**:
   - Capture and store face encodings for individuals who need to be recognized.

2. **Real-Time Recognition**:
   - Use a webcam to capture live video and detect faces.
   - Compare detected faces with the registered database.

3. **Mark Attendance**:
   - Log the attendance of recognized faces along with timestamps.
   - Export the data to a CSV file.

---

## Usage

### Register New Faces

1. Run the `register_faces.py` script:

```bash
python register_faces.py
```

2. Follow the prompts to capture face data for new users.

### Mark Attendance

1. Run the `mark_attendance.py` script:

```bash
python mark_attendance.py
```

2. The system will start the webcam and mark attendance for recognized faces.

### View Attendance

- Check the `attendance.csv` file for logged attendance data.

---

## Project Structure

```
attendance-face-opencv/
|── data/
|   ├── encodings/     # Stores face encodings
|   ├── images/        # Stores registered face images
|── attendance.csv      # Attendance log file
|── register_faces.py   # Script to register new faces
|── mark_attendance.py  # Script to mark attendance
|── requirements.txt    # Dependencies
|── README.md           # Project documentation
```

---

## Future Enhancements

- Integrate with a database (e.g., MySQL) for better scalability.
- Add a web-based or mobile-friendly interface.
- Implement notifications for missed attendance.
- Include support for multiple cameras.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contributing

Contributions are welcome! Please feel free to submit a pull request or report issues.

---

## Acknowledgments

- **OpenCV** for providing a robust computer vision library.
- **Face Recognition Library** for simplifying face encoding and recognition.

---

## Contact

If you have any questions or suggestions, feel free to contact me:

- **Email**: [your_email@example.com](mailto:p39salonisidheshwar@gmail.com)
- **GitHub**: [YourUsername](https://github.com/SaloniSidheshwar31)

Enjoy building and enhancing this project! 🚀


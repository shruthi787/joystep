# Joystep – Assistive Technology Suite

**Hands-Free Computer Control Using Hand Gestures and Facial Movements**

## 📌 Project Overview

Joystep is a Python-based assistive technology project designed to make computer interaction easier and more accessible through hand gestures and facial movements. The project explores an alternative to traditional mouse control using a webcam and computer vision.

It aims to support users with limited hand mobility by enabling cursor movement, clicking, and scrolling through supported gestures.

## 🎯 Objectives

- Develop a hands-free computer interaction system.
- Enable gesture-based mouse control.
- Explore facial movement-based cursor control.
- Improve accessibility through computer vision.
- Provide an affordable alternative input method using a webcam.

## ✨ Features

- **Hand Gesture Control:** Control the cursor using recognized hand movements.
- **Mouse Actions:** Perform supported left-click and right-click actions.
- **Scroll Control:** Use supported gestures to activate scrolling.
- **Face Control:** Explore hands-free cursor movement using facial movements.
- **Calibration:** Map facial or head movements to cursor positions.
- **Accessibility:** Provide alternative computer input methods.

*Note: Available features and gesture mappings depend on the current source-code implementation.*

## 🛠️ Technologies Used

- Python 3
- Computer Vision
- Webcam-based input
- Hand and facial movement recognition
- Visual Studio Code
- Git and GitHub

## 📁 Project Structure

```text
Joystep/
├── joystepp_3.py
├── README.md
├── requirements.txt
├── LICENSE
├── docs/
│   └── ARCHITECTURE.md
├── sample_data/
│   └── README.md
└── tests/
    └── test_basic.py
```

## 💻 System Requirements

- Windows, Linux, or macOS
- Python 3 installed
- A working webcam
- Git installed
- Required Python packages

## 🚀 Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/Shruthi1787/Joystep.git
```

### Step 2: Open the Project Folder

```bash
cd Joystep
```

Open this folder in Visual Studio Code.

### Step 3: Create a Virtual Environment

```bash
python -m venv .venv
```

Activate the environment on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

On macOS or Linux:

```bash
source .venv/bin/activate
```

### Step 4: Install Dependencies

If `requirements.txt` is present and contains the project's actual dependencies, run:

```bash
pip install -r requirements.txt
```

### Step 5: Run the Application

```bash
python joystepp_3.py
```

On Windows, you can also use:

```powershell
py joystepp_3.py
```

Ensure that your webcam is connected and that the application has permission to access it.

## 🖱️ How to Use

1. Start the application.
2. Ensure that the webcam is working.
3. Follow the instructions displayed by the application.
4. Use the supported hand gestures to perform computer actions.
5. Select face-based interaction if supported by the implementation.
6. Complete calibration when prompted.
7. Exit the application using its supported exit control.

## ⚙️ Environment Variables

The project currently has no documented environment variables.

If environment variables are introduced in future versions, document their names and purposes here. Never upload passwords, API keys, or other sensitive credentials to GitHub.

## 🧪 Testing

Run the automated tests using:

```bash
python -m unittest discover -s tests -v
```

Testing should cover:

- Application startup and Python syntax.
- Webcam availability.
- Hand gesture detection.
- Facial movement calibration.
- Cursor movement and mouse actions.
- Error handling when the camera is unavailable.

Hardware-dependent features should also be tested manually with a webcam.

## 🏗️ Architecture

The intended workflow is:

1. Webcam captures video frames.
2. Frames are processed by the computer vision pipeline.
3. The selected input mode determines whether hand or facial movements are analyzed.
4. Recognized movements are mapped to supported actions.
5. The application performs the corresponding cursor or mouse operation.

For more information, see [`docs/ARCHITECTURE.md`](docs/ARCHITECTURE.md).

## 🔒 Privacy and Security

- Webcam access is used for the intended application functionality.
- Avoid storing video recordings unnecessarily.
- Do not commit passwords, API keys, or private configuration files.
- Obtain consent before collecting or sharing personal images or recordings.

## ⚠️ Limitations

- Performance may depend on lighting conditions and webcam quality.
- Gesture recognition may require calibration.
- A working webcam is required for camera-based features.
- Actual supported gestures depend on the current implementation.

## 🔮 Future Enhancements

- Improve gesture recognition accuracy.
- Add customizable gesture controls.
- Improve cursor stability and calibration.
- Expand automated testing.
- Improve cross-platform compatibility.
- Introduce additional accessibility features.

## 👥 Contributors

- Shruthi
- Project teammate

## 📄 License

This project is distributed under the license specified in the [`LICENSE`](LICENSE) file.

---

**Joystep – Making computer interaction more accessible through assistive technology.**

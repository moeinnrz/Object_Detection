# 🎯 Live Object Detection with YOLO and PyQt5 GUI

## 📌 Project Introduction
This project is a desktop application that detects objects live from the system camera using the YOLOv8 model and the PyQt5 GUI. After clicking the `Start` button, the application takes an image from the camera, sends it to the YOLO model, and displays the output with a box and label on the detected objects.

![imgobjectdetection](https://github.com/user-attachments/assets/261b6fd5-4c1d-4da7-bc34-a6ab9b06a60f)

---

## 🧠 Applications

- Intelligent video surveillance
- Live video analysis for research projects
- Teaching machine vision and deep learning concepts
- Use in robotics and automation projects
- Counting or tracking specific objects

---

## 🔮 If the project is developed

In the future, the following features can be added to the project:

- Automatic storage of detected images or videos
- Support for multiple cameras at the same time
- Display a statistical graph of detected objects
- Connect to the Internet and send alerts (email, messenger, etc.)
- Apply filters only based on specific objects (for example, only humans or cars)

---

## 📚 Libraries used

- [`PyQt5`](https://pypi.org/project/PyQt5/) : Graphical interface design
- [`opencv-python`](https://pypi.org/project/opencv-python/) : Receive camera frames and process images
- [`ultralytics`](https://pypi.org/project/ultralytics/) : YOLOv8 model for object recognition
- `sys` and `QtCore`, `QtGui`, `QtWidgets` : main components of the program

---

## 🧰 Prerequisites

| Tool or version | Description |
|--------------|--------|
| Python 3.10 or lower | Higher versions may be incompatible with PyQt5 |
| pip | to install libraries |
| System camera | to get live image |

---

## 📦 Installation and setup

1. First install Python version 3.10 or lower.
2. Then install the libraries via the following file:
```bash
pip install -r requirements.txt
```

3. Run the program:
```bash
python main.py
```

---

## 💡 Second method of execution (without Python)

If you have the executable file (`.exe`) of the program, you can use the project just by running it. In this case, there is no need to install Python or libraries.

You can use PyInstaller to create the executable file:

pip install pyinstaller
pyinstaller --onefile --noconsole main.py

The output is saved in the `/dist` path.

---

## 📁 Create requirements.txt

To create a `requirements.txt` file from your system:

pip freeze > requirements.txt

---

## 👨‍💻 Developer

> Designed and developed by: **Moein**
> GitHub: https://github.com/moeinnrz
> Year of production: 2025

---

## 🟢 License
This project is released under a free license for educational purposes.

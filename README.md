
# 👁️ ClearPath - Object Detection & Distance Estimation for the Visually Impaired

This project uses a YOLOv8 model to detect nearby objects in real time via a webcam and estimates their distance. It then announces these objects using voice notifications.

## 📦 Requirements

- Python 3.8+
- Jupyter (for interactive usage)
- Virtual environment (recommended)

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/AyoubFanaoui/clearPath.git
cd clearPath
```

### 2. Create a Virtual Environment + Jupyter Kernel

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=clearpath-kernel --display-name "Python (ClearPath)"
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 💡 Notes

- The webcam will open and start detecting objects. The system will verbally announce nearby objects and estimate their distance.
- Press **Q** to exit the detection window.
- Focal length is currently set to 462 — for better accuracy, calibrate it using known objects and distances.
- The app estimates distance based on the object's width in pixels and real-world width.

## 📷 Use Cases

- Assistive technology for visually impaired individuals
- Real-time object detection and voice guidance
- Smart navigation for robotics and embedded systems

You can get the full list from [COCO official classes](https://github.com/pjreddie/darknet/blob/master/data/coco.names).

## 👩‍💻 Author

Build with passion and ❤️ by 👩‍💻 [https://github.com/SoukainaLAKBICHI2]


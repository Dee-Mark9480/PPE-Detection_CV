# PPE-Detection_CV
🦺 PPE Detection using YOLO This repository demonstrates Personal Protective Equipment (PPE) detection using a pre-trained YOLO model. The model can identify safety gear such as helmets, vests, and masks in images and videos.


🚀 Project Overview
Ensuring worker safety is essential in industries like construction, manufacturing, and healthcare. This project uses a YOLO-based object detection model to recognize PPE compliance in real-time.

✅ PPE Detection: Identifies if a person is wearing safety gear (e.g., hardhat, vest, mask).
✅ Compliance Check: Compares detected PPE against required gear for jobs like construction, carpentry, etc.
✅ Works on Images, Videos, and Live Webcam Feeds
✅ Real-time Alerts for Missing PPE


📂 Model Used
We have used YOLOv8 with a trained model file ppe.pt. This model has been trained on images of people wearing and missing PPE kits.
The ```ppe.pt``` model file is too large to be stored on GitHub. You can download it from:
[Download PPE Model (ppe.pt)](https://drive.google.com/drive/folders/1gwh-KbEHGqHxiY3IyuQlYCoUPjFs_SoM)
After downloading, place it in the project directory.


🛠️ Installation & Setup

1️⃣ Install Dependencies
- Ensure Python is installed, then run:
  - ```pip install ultralytics opencv-python cvzone numpy```

2️⃣ Verify YOLOv8 Installation
- To check if YOLOv8 is installed correctly, run:
```python -c "from ultralytics import YOLO; print(YOLO('yolov8n.pt'))"```

2️⃣ Download the Trained YOLO Model
- Place the .pt model file (ppe.pt) in the project directory.

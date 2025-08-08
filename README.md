# 🚗 Real-Time Object Detection Using OpenCV & SSD MobileNet

This project demonstrates real-time object detection using the **SSD MobileNet V3** model and **OpenCV**. The model detects objects from the COCO dataset and groups relevant object classes (like `car`, `bus`, `truck`) under a common label: **Vehicle**.

---

## 🔍 Features

- ✅ Real-time video object detection
- ✅ SSD MobileNet V3 pre-trained on COCO dataset
- ✅ Classification of vehicles (`car`, `truck`, `bus`, etc.) under a single label
- ✅ Displays bounding boxes and confidence scores
- ✅ Supports both webcam and video file input
- ✅ Option to preview or save the output

---

## 📁 File Structure

```bash
.
├── vehicle_detection.py         # Main Python script
├── labels.txt                   # COCO class labels (80 classes)
├── ssd_mobilenet_v3.pb         # Pre-trained frozen model
├── ssd_mobilenet_v3.pbtxt      # Configuration file
└── README.md                    # This file

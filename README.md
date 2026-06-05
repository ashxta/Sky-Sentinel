# ✈️ SkySentinel

> Real-Time Edge AI for Aircraft Inspection & Defect Detection

SkySentinel is an Edge AI-powered aircraft inspection system that automates structural defect detection using computer vision and deep learning. The system performs real-time defect identification directly on edge devices, reducing inspection time, minimizing human error, and eliminating dependency on cloud connectivity.

Built for aviation maintenance and MRO (Maintenance, Repair & Overhaul) operations, SkySentinel enables faster, safer, and more cost-effective aircraft inspections.

---

## 🚀 Features

- 🔍 Real-time aircraft defect detection
- 🛩️ Crack identification
- 🛠️ Corrosion detection
- ⚠️ Dent and structural anomaly detection
- 🎨 Paint degradation analysis
- 📍 Defect localization with bounding boxes
- 📊 Severity-based defect classification
- 💾 Offline edge deployment
- 📑 Automated inspection reports
- 📈 Inspection dashboard and analytics

---

## 🏗️ System Architecture

```text
Aircraft Images / Video
           │
           ▼
      OpenCV Pipeline
           │
           ▼
      YOLOv8 Detection
           │
           ▼
    Defect Classification
           │
           ▼
     Severity Assessment
           │
           ▼
 Dashboard & Inspection Report
```

---

## 🧠 Technologies Used

### AI / Machine Learning
- YOLOv8
- PyTorch
- ONNX Runtime
- TensorFlow Lite

### Computer Vision
- OpenCV
- NumPy
- Pillow
- Albumentations

### Edge Computing
- NVIDIA Jetson Nano
- Raspberry Pi
- TensorRT
- ONNX Optimization

### Data & Dashboard
- SQLite
- Pandas
- Streamlit
- Power BI

---

## 🎯 Defect Classes

SkySentinel can identify:

| Defect Type | Description |
|------------|-------------|
| Crack | Structural surface cracks |
| Corrosion | Rust and corrosion regions |
| Dent | Surface deformation |
| Paint Damage | Paint fading and peeling |
| Surface Anomalies | Other visual defects |

---

## 📊 Expected Performance

| Metric | Target |
|----------|---------|
| Detection Accuracy | > 92% |
| Inference Latency | < 100 ms |
| Inspection Time Reduction | 60–70% |
| Model Compression | 4× using Quantization |

---

## 💡 Innovation

Unlike traditional inspection systems, SkySentinel:

✅ Runs completely offline

✅ Performs on-device inference

✅ Provides real-time defect detection

✅ Works in remote hangars and airfields

✅ Eliminates cloud dependency

✅ Generates automated inspection reports

---

## 🔄 Workflow

1. Capture aircraft images using camera/drone.
2. Preprocess images using OpenCV.
3. Run YOLOv8 inference on edge device.
4. Detect and classify defects.
5. Assign severity score.
6. Generate inspection dashboard and reports.

---

## 📈 Future Enhancements

- Autonomous drone-based inspections
- Digital twin integration
- Predictive maintenance analytics
- Fleet-level monitoring dashboard
- LiDAR-assisted inspection
- Multi-aircraft inspection management

---

## 🏆 Use Cases

- Aircraft Maintenance (MRO)
- Airline Safety Inspections
- Aerospace Manufacturing QA
- Defense Aircraft Inspection
- Remote Airfield Operations

---

## 👥 Team

Team SkySentinel

Developed for **Tata InnoVent 2027**

---

## 📄 License

This project is developed for educational, research, and innovation purposes.

---

### SkySentinel
**Edge AI for Intelligent Aircraft Inspection**

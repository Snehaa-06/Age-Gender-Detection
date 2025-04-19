# 🧠 Age-Gender Detection using YOLOv8

This project focuses on detecting **age and gender** from facial images using the YOLOv8 object detection model. It leverages deep learning and computer vision techniques to predict both age and gender in real time or from uploaded datasets.

---

## 📁 Files Overview

- `age_gender_2000/` — Contains dataset or image samples used for training/testing  
- `age_gender_YOLOV8.ipynb` — Jupyter Notebook for training/testing the YOLOv8 model  
- `runs/` — Contains results, saved models, and predictions

---

## 🚀 Tech Stack

- Python 🐍  
- YOLOv8 (Ultralytics)  
- OpenCV  
- Pandas / NumPy  
- Google Colab / Jupyter Notebook

---

## 📦 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Snehaa-06/Age-Gender-Detection.git
   cd Age-Gender-Detection
   
2. Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Or manually install Ultralytics and other necessary libraries like OpenCV.

3. Run the Notebook

Open age_gender_YOLOV8.ipynb in Jupyter or Google Colab

Follow the steps to train/test the model

**📊 Output Example**
The model returns bounding boxes with predicted:

🧑 Gender: Male / Female

🎂 Age: e.g., "Age-45"

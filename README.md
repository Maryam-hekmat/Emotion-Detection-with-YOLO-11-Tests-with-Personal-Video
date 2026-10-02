🌐 Portfolio: https://maryamhekmatai.com/
#Emotion-Detection-with-YOLO-11-Tests-with-Personal-Video
Emotion detection with YOLO 11 Test with personal video Using my own personal video and with YOLO 11 I was able to conduct a successful test
# Emotion-Detection-with-YOLO-11-Tests-with-Personal-Video
Emotion detection with YOLO 11 Test with personal video Using my own personal video and with YOLO 11 I was able to conduct a successful test
# 🎬 Emotion Detection from Personal Video using YOLOv11

## 🧠 Project Overview
This project focuses on real-time emotion detection from a personal video using the YOLOv11 deep learning model.  
The model was trained on a facial expression dataset and then tested on a real personal video to evaluate performance in real-world conditions.

The system processes video frames, detects faces, classifies emotions, and generates an output video with emotion labels and confidence scores displayed on each detected face.

This project demonstrates practical implementation of computer vision and deep learning for emotion recognition.

---

## 🚀 Key Features
- Emotion detection using YOLOv11  
- Training on facial expression dataset  
- Testing on real personal video  
- Output video generation with predictions  
- Fast experimental training for demonstration  
- Ready for further improvement and scaling  

---

## ⚙️ Technologies Used
- Python  
- YOLOv11 (Ultralytics)  
- OpenCV  
- Deep Learning / Computer Vision  
- Kaggle Notebook (GPU T4)

---

## 📂 Dataset
The model was trained using a facial expression dataset prepared in YOLO format.

Example emotion classes:
- Happy  
- Sad  
- Angry  
- Sleepy  
- Neutral  
- Surprise  

The dataset includes labeled facial images for training and validation.

---

## 🏋️‍♂️ Training Details
The model was trained with a small number of epochs for quick testing and demonstration purposes.

For better performance and accuracy in future versions:
- Increase number of epochs  
- Use larger and more diverse dataset  
- Apply data augmentation  
- Tune hyperparameters  
- Use higher resolution images  

This version is a fast experimental build to demonstrate the full pipeline from training to real video testing.

---

## 🎥 Personal Video Testing
After training, the model was tested on a real personal video.

The output video includes:
- Face detection  
- Emotion prediction  
- Confidence score  
- Bounding boxes around faces  

Due to privacy and file size considerations, the personal video is not uploaded publicly to this repository.

---

## 📊 Output
The model generates:
- Trained weights  
- Training plots and metrics  
- Output video with detected emotions  

Output video can be downloaded from:

--

## 🛠️ How to Run the Project
1. Upload dataset in YOLO format  
2. Train the model using YOLOv11  
3. Load trained weights  
4. Run inference on a video  
5. Download the output video  

Example inference code:
```python


from ultralytics import YOLO

model = YOLO("best.pt")
results = model("your_video.mp4", conf=0.5, save=True)

## 🎥 Demo Video

The personal test video is not included in this repository for privacy reasons.

However, the demo output video showing real emotion detection results is available upon request.  
Feel free to contact me if you'd like to see the full demo.

LinkedIn address: https://www.linkedin.com/in/maryam-hekmat-85905137a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app

Email address: maryamhekmat166@gmail.com

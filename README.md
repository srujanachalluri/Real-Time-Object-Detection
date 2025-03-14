# 🚀 Real-Time Object Detection using TensorFlow & OpenCV  

🔍 A powerful real-time object detection system using TensorFlow Object Detection API and OpenCV. This project leverages the SSD MobileNet model to detect multiple objects from a live webcam stream with high accuracy and speed.

# 📌 Features
✅ Real-time object detection from webcam/video input.  
✅ Pre-trained SSD MobileNet model for high-speed detection.  
✅ Uses TensorFlow Object Detection API for deep learning inference.  
✅ 90-class detection from the COCO dataset.  
✅ Efficient bounding box visualization using OpenCV.  
  
## 🛠 Tech Stack  
  Language: Python 🐍  
  Framework: TensorFlow  
  Libraries: OpenCV, NumPy, matplotlib  
  Model: SSD MobileNet v1 (Pre-trained on COCO dataset)  

## 📥 Installation  
  1️⃣ Clone the Repository  
        **git clone https://github.com/srujanachalluri/real-time-object-detection.git**   
        **cd real-time-object-detection**  
  2️⃣ Install Dependencies
        **pip install -r requirements.txt**  
  3️⃣ Download the TensorFlow Model  
        **wget http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v1_coco_11_06_2017.tar.gz**  
        **tar -xvzf ssd_mobilenet_v1_coco_11_06_2017.tar.gz**  
  4️⃣ Run the Object Detection  
        **python finalproject.py**  


## 📌 Code Explanation  
  🔹 finalproject.py (Main Script)  
    -> Loads a pre-trained SSD MobileNet model from TensorFlow’s Model Zoo.  
    -> Uses OpenCV to capture frames from the webcam.  
    -> Runs inference using the TensorFlow Object Detection API.  
    -> Draws bounding boxes & labels on detected objects.  
    -> Stops when the user presses 'q'.  


  🔹 Core Functions in detect.py  

  Function --------------------Description  
  download_model() ------------Downloads and extracts the SSD MobileNet model  
  load_model()	-------------- Loads the frozen TensorFlow model  
  detect_objects(frame) ------ Runs object detection on each frame  
  visualize_boxes()	---------- Draws bounding boxes on detected objects  


 ## 📈 Sample Results  
  Object----Confidence-----Bounding Box  
  Person---- 95%-----------(320, 240)  
  Car	  ----  87% ---------(100, 300)  


 ## 🚀 Future Improvements  
  🔹 Upgrade to YOLOv8 for faster detection.  
  🔹 Deploy as a Flask API for real-time streaming.  
  🔹 Integrate AWS Lambda & S3 for cloud inference.  

## 📫 Contact Me  
  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/srujana-challuri-b63b18160)  
  [![GitHub](https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github)](https://github.com/srujanachalluri)  


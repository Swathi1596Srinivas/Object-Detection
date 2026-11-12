# Object-Detection


📌 Project Overview

Object Detection is a computer vision project designed to identify and locate objects in images or video using deep learning techniques.

The project uses the YOLOv8 (You Only Look Once) object detection model to detect multiple objects and draw bounding boxes around the detected objects. An application interface is provided through Python to make the object detection process easier to use.

🎯 Objectives

- Detect objects from images and video.
- Identify different object classes.
- Locate detected objects using bounding boxes.
- Display prediction confidence scores.
- Perform real-time object detection.
- Provide an easy-to-use application for testing the model.

🛠️ Technologies Used

- Python – Programming language
- YOLOv8 – Object detection model
- Ultralytics – YOLOv8 implementation
- OpenCV – Image and video processing
- NumPy – Numerical operations
- Streamlit – Application interface

📂 Project Structure

Object-Detection/
│
├── README.md
├── app.py
├── yolov8n.pt
└── ...

🤖 Model Used

YOLOv8

YOLOv8 is a deep learning-based object detection model that can detect objects in an image or video in a single processing step.

The model provides:

- Object class
- Bounding box location
- Confidence score

For example, when an image contains a person, car, or other objects, YOLOv8 identifies the objects and marks their locations using bounding boxes.

🔄 Project Workflow

Input Image / Video
        ↓
Image Preprocessing
        ↓
YOLOv8 Object Detection
        ↓
Object Classification
        ↓
Bounding Box Generation
        ↓
Confidence Score
        ↓
Detection Result

🔍 How It Works

1. The user provides an image or video as input.
2. The application processes the input using the YOLOv8 model.
3. YOLOv8 identifies objects present in the input.
4. Bounding boxes are generated around the detected objects.
5. Each detected object is assigned a class label.
6. A confidence score is displayed for each prediction.
7. The final detection result is shown to the user.

📊 Detection Output

The output contains:

- Object Name – Name of the detected object.
- Bounding Box – Location of the object in the image.
- Confidence Score – Probability/confidence of the detection.

Example:

Person    → 0.92 confidence
Car       → 0.87 confidence
Dog       → 0.81 confidence

🚀 Application

The project can be used for:

- Real-time object detection
- Image analysis
- Video surveillance
- Traffic monitoring
- Smart camera applications
- Computer vision research
- Educational purposes

▶️ How to Run the Project

1. Clone the Repository

git clone https://github.com/Swathi1596Srinivas/Object-Detection.git

2. Navigate to the Project Folder

cd Object-Detection

3. Install Required Libraries

pip install ultralytics opencv-python streamlit numpy

4. Run the Application

If the application is built using Streamlit:

streamlit run app.py

The application will open in the browser.

📌 Model File

The repository contains:

yolov8n.pt

This is the YOLOv8 Nano pretrained model, designed to provide fast object detection while requiring relatively fewer computational resources.

💡 Key Features

- Fast object detection
- Multiple object detection
- Bounding box visualization
- Confidence score display
- Image/video processing
- Easy-to-use application interface
- Deep learning-based computer vision

🌍 Real-World Applications

Object detection technology can be applied in:

- Autonomous vehicles
- Security and surveillance
- Retail analytics
- Traffic management
- Industrial automation
- Smart city systems
- Agriculture
- Healthcare imaging
- Robotics

🔮 Future Enhancements

- Add custom object detection using a trained dataset.
- Improve detection accuracy.
- Add webcam-based real-time detection.
- Support multiple image and video formats.
- Deploy the application to the cloud.
- Add object counting functionality.
- Add object tracking using tracking algorithms.
- Create performance reports for detected objects.

⚠️ Limitations

Object detection performance can depend on:

- Image quality
- Lighting conditions
- Object size
- Background complexity
- Model configuration
- Available computing resources

👩‍💻 Author

P.V. Swathi

This project was developed as a computer vision application for detecting and locating objects using deep learning and YOLOv8.

# SHADY: Intelligent Fall Detection Using YOLOv8


# SHADY is an AI-powered application for detecting falls using computer vision techniques. It leverages YOLOv8 for real-time object detection and integrates with a database for storing and analyzing results. The project is designed to provide robust fall detection capabilities for safety-critical applications.


###   Features  ##
1.Real-time fall detection using YOLOv8.
2.Integration with a SQLite database for data management.
3.Video processing and result visualization.
4.Pretrained YOLOv8 model for high accuracy.
5.Sample video (fall.mp4) for demonstration.



# Requirements
The project requires the following tools and libraries:

1.Python 3.7 or later
2.Required libraries (from requirements.txt)
3.OpenCV
4.Flask (for app.py)
5.SQLite
6.PyTorch (for YOLOv8)
7.NumPy, Matplotlib, and other common libraries
8.Jupyter Notebook (if using the .ipynb file for training or experimentation)
9.Platform
10.OS: Linux, macOS, or Windows
11.Frameworks: PyTorch, Flask





####  Steps to Implement #######
# Clone the Repository

-----bash-----
# step-1(Copy code)
git clone https://github.com/abhijeetsawant11/SHADY-Smart-Human-Activity-Detection-using-Yolo

# step-2
cd SHADY
Install Dependencies Install all required libraries:

-----bash-----
step-3(Copy code)
pip install -r requirements.txt
Run the Fall Detection

# step-4(Test on the provided video (fall.mp4):
bash
Copy code
python YOLO_Video.py
Use the Web Application

# step-5(Start the Flask application:)
bash
Copy code
python app.py
Access the application at http://127.0.0.1:5000.
Customize and Train

# step-6
To customize YOLOv8 for a custom dataset, use the Jupyter Notebook:
bash
Copy code
jupyter notebook yolov8_object_detection_on_custom_dataset.ipynb



### Algorithm ##
1.Preprocessing:
Read the video or real-time feed.
Perform frame-by-frame processing.

2.Fall Detection:
Use YOLOv8 for object detection.
Analyze the detected object's trajectory or posture to identify falls.

3.Postprocessing:
Save results to the SQLite database.
Display the detected events.
Visualization:

Annotate frames with detections and display them in real-time.





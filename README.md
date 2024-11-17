SHADY: Intelligent Fall Detection Using YOLOv8


SHADY is an AI-powered application for detecting falls using computer vision techniques. It leverages YOLOv8 for real-time object detection and integrates with a database for storing and analyzing results. The project is designed to provide robust fall detection capabilities for safety-critical applications.


Features
Real-time fall detection using YOLOv8.
Integration with a SQLite database for data management.
Video processing and result visualization.
Pretrained YOLOv8 model for high accuracy.
Sample video (fall.mp4) for demonstration.



Requirements
The project requires the following tools and libraries:

Python 3.7 or later
Required libraries (from requirements.txt)
OpenCV
Flask (for app.py)
SQLite
PyTorch (for YOLOv8)
NumPy, Matplotlib, and other common libraries
Jupyter Notebook (if using the .ipynb file for training or experimentation)
Platform
OS: Linux, macOS, or Windows
Frameworks: PyTorch, Flask





Steps to Implement
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/SHADY.git
cd SHADY
Install Dependencies Install all required libraries:

bash
Copy code
pip install -r requirements.txt
Run the Fall Detection

Test on the provided video (fall.mp4):
bash
Copy code
python YOLO_Video.py
Use the Web Application

Start the Flask application:
bash
Copy code
python app.py
Access the application at http://127.0.0.1:5000.
Customize and Train

To customize YOLOv8 for a custom dataset, use the Jupyter Notebook:
bash
Copy code
jupyter notebook yolov8_object_detection_on_custom_dataset.ipynb



Algorithm
Preprocessing:

Read the video or real-time feed.
Perform frame-by-frame processing.
Fall Detection:

Use YOLOv8 for object detection.
Analyze the detected object's trajectory or posture to identify falls.
Postprocessing:

Save results to the SQLite database.
Display the detected events.
Visualization:

Annotate frames with detections and display them in real-time.





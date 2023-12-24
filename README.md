# Cars-Counter-using-YOLOv8
This repository contains Python code to count the number of cars, trucks, buses, and motorbikes in a video using YOLOv8 object detection. It also tracks the detected vehicles and displays the count in real-time.

Car Counter ![image](https://github.com/biswadeep-roy/Cars-Counter-using-YOLOv8/assets/74821633/1e28822d-7e84-4c1a-b736-a7d58b63f9c8)


Requirements
Before running the code, make sure you have the following Python modules installed:  

numpy
opencv-python
cvzone
ultralytics
sort
You can install these modules using pip with the following commands:

`pip install numpy opencv-python cvzone ultralytics
pip install git+https://github.com/abewley/sort.git
`

# Usage
Clone the repository:

`git clone https://github.com/biswadeep-roy/cars-counter-yolov8.git
`

Download the YOLOv8 weights file (e.g., yolov8l.pt) and place it in the root directory of the repository.

Create a mask image for region of interest (ROI) using a tool like Canva. Save the mask as mask.png and place it in the root directory of the repository.

Run the code:

`python Car_Counter.py
`

The code will open a video stream and display the vehicles detected in real-time. It will also count the number of vehicles that cross a predefined line in the video.

# Customization

You can modify the classNames list to include or exclude specific object classes for detection.
Adjust the confidence threshold (conf > 0.3) to control the detection sensitivity.
Modify the limits list to change the position of the counting line in the video.

# License

This project is licensed under the MIT License - see the LICENSE file for details..
 
# Acknowledgments

YOLOv8: Ultralytics YOLOv5 GitHub Repository
SORT (Simple Online and Realtime Tracking): SORT GitHub Repository

# People-Detection-using-webcam
PeopleCount - Real-time People Detection and Tracking

This project detects and tracks people in real-time from a webcam or IP camera using YOLOv5 and OpenCV. It logs the detection history (first and last seen times) of each individual detected and stores this information in a CSV file.

Features

Real-time detection and tracking of people.
Logs the first and last seen timestamps of each detected person.
Supports webcam or IP camera input.
Saves detection history in people_history.csv.
Requirements

Python 3.10 or above
Libraries:
torch
opencv-python
pandas
yolov5 (via torch.hub)
You can install the required libraries with the following:

pip install torch opencv-python pandas
Installation

Clone or download the repository:
git clone https://github.com/your-username/PeopleCount.git
cd PeopleCount
Install dependencies:
pip install -r requirements.txt
Make sure that your webcam or IP camera is set up and functional.
Usage

Run the application using:
python3 app.py
The application will open the webcam (or IP camera stream) and start detecting people. For each person detected, it will show the bounding box along with a unique ID, and the first and last seen timestamps are logged.
Press q to quit the application.
After the session, the people_history.csv file will be updated with a record of all detected people, including their first and last seen times.

# YOLO Real-Time Object Detection
Fork of YOLO real-time object detection with pretrained PascelVOC dataset.

## Requirements
Tensorflow, OpenCV, Pafy, Devicehive, Six

or just run `pip install -r requirements.txt`

Download and extract [data](https://s3.amazonaws.com/video-analysis-demo/data.tar.gz "YOLO Neural Network") folder to the project.

## Running
To run the program with camera output type `python eval.py`

To run the program from a video output type `python eval.py --video="/path_to_video_file.mp4"`

To run the program from YouTube video type `python eval.py --video="youtube_url"`

## Key-bindings
Q - Quit

S - Save current frame as an image

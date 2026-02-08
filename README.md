# YOLOv8 Video Object Detection

This project performs object detection on a video using YOLOv8.
It processes each frame, detects objects, saves annotated frames, and rebuilds an output video.

## What This Project Does
- Loads a pretrained YOLOv8 model.
- Reads a video file frame by frame.
- Runs object detection on each frame.
- Saves detected frames as images.
- Combines saved frames into a new output video.

## Tech Stack
- Python 3
- Ultralytics YOLOv8
- OpenCV

## Model Used
- YOLOv8 Nano pretrained model.
- File used. `yolov8n.pt`.

## Input
- Video file for detection.
- Example. `cars video for detection.mp4`.

## Output
- Annotated image frames.
- Final processed video. `yolo_output_video.mp4`.

## Project Workflow
- Install required libraries.
- Load YOLOv8 model.
- Open input video.
- Read frames in a loop.
- Perform object detection on each frame.
- Draw bounding boxes and labels.
- Save each processed frame as an image.
- Merge all frames into a single output video.

## How to Run
- Clone the repository.
- Place the input video in the project folder.
- Run the Python file.

```bash
python yolo_detection.py

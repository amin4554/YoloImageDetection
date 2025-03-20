## YoloImageDetection
# Installation & Setup
1. Install Dependencies

Before running the script, ensure you have Python installed. You will also need the following Python packages:

```sh
pip install ultralytics opencv-python torch torchvision numpy
```

2. Download YOLOv8 Model

The script uses YOLOv8n (the nano version) by default. You can download the model directly from Ultralytics.

If you want better accuracy, you can replace "yolov8n.pt" with "yolov8s.pt" or a larger model like "yolov8m.pt".

# How to Use the Code
1. Place Your Video File

Make sure you have a video file named srh.mp4 in the same directory as the script. You can also change the filename in the script if needed.
2. Run the Script

Execute the script with:

python yolo_object_detection.py

The script will:

    Load the YOLOv8 model
    
    Process the input video frame by frame
    
    Detect objects and draw bounding boxes
    
    Save the output as "output.mp4"
    
    Display the processed video in real time

To exit early, press 'q' while the video is playing.

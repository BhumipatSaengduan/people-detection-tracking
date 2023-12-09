# People Detection and Tracking with YOLOv8 and DeepSORT

> detects and tracking people in a video/webcam

This notebook implements people detection and tracking using:
- **YOLOv8** for object detection.
- **DeepSORT** for object tracking.
- **OpenCV** for video processing and visualization.

## Features
- Detects "person" class with YOLOv8.
- Tracks detected objects with DeepSORT.
- Visualizes bounding boxes and IDs for tracked objects in real-time.


## Getting Started

### Prerequisites
1. **Python Environment**: Python 3.8 or higher
2. **Virtual Environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate    # On Linux/Mac
   venv\Scripts\activate       # On Windows
   ```
3. **Install Requirements**:
   ```bash
   pip install -r requirements.txt
   ```
   Libraries:
   - `Python` 3.8+
   - `Jupyter`
   - `YOLOv8` (`ultralytics` library)
   - `DeepSORT` (`deep-sort-realtime`)
   - `OpenCV`
   - `Numpy`
   - `gdown`

### Running the Notebook
1. **Starts the Jupyter**:
   Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Open and run the notebook `people-detection-deepsort.ipynb` to process the video, detect people, and track them in real-time.

2. **Stopping the Process**:
   Press `q` to stop processing and close the video window.

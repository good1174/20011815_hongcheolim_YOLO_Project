# YOLO Object Detection with Ultralytics

## Project Description
This notebook demonstrates object detection using the Ultralytics YOLO models. It includes steps for loading the necessary libraries, downloading a pre-trained YOLO model (e.g., `yolo26n.pt` and `yolo26s.pt`), and performing inference on example images. The detected objects are then displayed with bounding boxes.

## Setup and Installation
To run this notebook, ensure you have the following libraries installed:
- `ultralytics`
- `opencv-python`
- `torch`
- `numpy`
- `Pillow`

These are typically installed in a Colab environment, or you can install them using `pip install <package_name>`.

## Usage
1. Run the initial cells to import libraries and check GPU availability.
2. Load the YOLO model of your choice (e.g., `YOLO("yolo26n.pt")`).
3. Upload your images or use the provided example images in `/content/examples`.
4. Execute the cells that perform object detection using `model.predict()` and display the results.

## Models Used
- `yolo26n.pt`: A nano-sized YOLO model for fast inference.
- `yolo26s.pt`: A small-sized YOLO model offering a balance between speed and accuracy.

## Output
The results of the object detection, including images with detected objects and their bounding boxes, are displayed directly in the notebook.

### 🔹 Analysis Script

- **`compara_yolo.ipynb`**

  Jupyter Notebook used to perform the comparative analysis between
  YOLOv2, YOLOv3 and YOLOv8 detection results.

  The notebook implements the following steps:

  1. Loading the input image test2.jpeg used for all models;
  2. Creating the numerical output files:
     - YOLOv2 (`yolov2_output.txt`);
     - YOLOv3 (`yolov3_output.txt`);
     - YOLOv8 (`yolov8_output.json`);
  3. Parsing bounding box coordinates, confidence scores and class labels
     for each detected object.

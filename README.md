# DeepFashion_model
---

## Fashion Object Detection using YOLOv8

### Overview

This project focuses on training a YOLOv8 model for fashion object detection. The following steps outline the flow involved in the project:

### Flow Involved

- **Data Preparation**:
  - Selected 1000 random images from the dataset and processed them locally due to the dataset's large size.
  - Extracted annotations in MSCOCO format and converted them into YOLO format.

- **Data Transformation**:
  - Uploaded YOLO-labeled images to RoboFlow software.
  - Split dataset into 8:1:1 ratio for training, validation, and testing.
  - Converted data into YOLOv8 format using RoboFlow.

- **Dataset Handling**:
  - Imported the dataset to Google Drive for ease of access.
  - Utilized the dataset for training, validation, and prediction tasks.

- **Model Initialization**:
  - Initialized model weights using the yolov8-seg model.
  - Configured model inputs and hyperparameters through the configuration file.
  - Fine-tuned hyperparameters for improved performance.

- **Model Training and Evaluation**:
  - Stored training results in the results directory, with the best performing model saved as best.pt.
  - Validated the trained model using the validation image directory.
  - Performed predictions on the test directory.

- **Model Optimization**:
  - Optimized the PyTorch model to the ONNX format for improved efficiency.

- **Visualization**:
  - Selected an image from the test directory and visualized the model's predictions.

### Requirements

- Python 3.x
- PyTorch
- Ultralytics YOLO
- RoboFlow
- Google Drive

### Usage

1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Follow the flow described above for training and testing the YOLOv8 model.
4. Visualize the model's predictions on test images for evaluation.

### Results

The trained YOLOv8 model demonstrates efficient fashion object detection on test images, providing valuable insights for various applications in the fashion industry.

---

Flow Involved :


> From the dataset 1000 random images were selected and were done on the local system due to large size of the initial dataset.


>The annotations of these images were extracted which were present in the MSCOCO format and were converted into YOLO format.


>The YOLO labels along with their corresponding images were uploaded to the RoboFlow software and were splitted into 8:1:1 ratio and were converted into the YOLOv8 format.


>The dataset was imported to the drive and was used for the training , validation and prediction.


>The model was initialized with the weights of the yolov8-seg model on which the data was trained.


>All the inputs were taken from the configuration file for the training of the model and the hyperparameters were modified for fine tuning.


>The results were stored in the results directory with the best weighted model as best.pt.


>The trained model was then validated with the help of the validation image directory.


>The model predicted the results on the test directory.


>The PyTorch model was optimized to the ONNX format.


>An image was selected from the test directory and the results were visualized .
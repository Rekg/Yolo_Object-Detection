# Yolo_Object-Detection
# Object_Detection Implementation Steps
Set Up
- Configure Roboflow API Keys
# Install yolo11 via ultralytics
# Fine tune Yolo11
  Download dataset using roboflow sdk
  rf = Roboflow(api_key=ROBOFLOW_API_KEY)
  project = rf.workspace("huyifei").project("tft-id")
  version = project.version(1)
  dataset = version.download("yolov11")
# Custom Training
# use some batches for validation
# Deploy model on roboflow

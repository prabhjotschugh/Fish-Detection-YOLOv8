# 🐟 Fish Detection using YOLOv8
This repository contains code to detect fish using the Ultralytics YOLOv8 model. The model is trained on a custom fish tracking dataset and provides accurate detection and localization of fish.

### 📜 Project Overview
This project is designed to detect and localize fish in images using the YOLOv8 model. The key steps involved in this project include:

- **Data Preparation:** Converting XML annotations to YOLO format and splitting data into training and validation sets.
- **Model Training:** Training the YOLOv8 model on the prepared dataset with various augmentations and configurations.
- **Model Evaluation:** Visualizing detection results and plotting training and validation losses.
## 🌟 Key Features
### 📁 XML to YOLO Conversion
- Converts XML annotations from the fish tracking dataset to YOLO format.
- Extracts bounding box coordinates and converts them to the format required by YOLO.
### 🔀 Train/Val Split
- Automatically splits the dataset into training and validation sets.
- Ensures a proper balance between training and validation samples for robust model evaluation.
### 🏋️‍♂ Model Training
- Utilizes the YOLOv8 model with a comprehensive training pipeline.
- Configures various training parameters including epochs, image size, batch size, and data augmentations.
- Provides options for using different optimizers and other training enhancements.
### 📊 Visualization
- Displays detection results with bounding boxes and confidence scores.
- Plots training and validation losses for both box and class predictions to monitor training progress.
### 🚀 How to Use
**1. Data Preparation:** Run the provided scripts to prepare the dataset. This includes copying the dataset, converting XML annotations to YOLO format, and splitting the data into training and validation sets.

**2. Model Training:** Train the YOLOv8 model using the configured parameters. Adjust training parameters as needed to optimize performance.

**3. Visualization:** View the detection results and evaluate the model's performance using the provided scripts.
## 📈 Results
After training, you can visualize the detection results and evaluate the model's performance. The following sections show examples of the output you can expect.

### 🖼️ Example Output
**🐠 Detection Visualization**
After running the detection script, you will get images with detected fish, bounding boxes, and confidence scores. Here is an example:

<p align="center">
  <img src="https://github.com/user-attachments/assets/6d235be6-15e1-4266-8e62-e198db6e948d"/>
</p>

**📉 Training and Validation Losses**
During training, the model logs box and class losses for both training and validation sets. These losses are plotted to help you monitor the training process:

<p align="center">
  <img src="https://github.com/user-attachments/assets/e3709277-ca6a-4b16-b592-97c4476c3e3f" width="700"/>
</p>

### 🎯 Conclusion
This project demonstrates how to use the YOLOv8 model for fish detection. The comprehensive pipeline from data preparation to model training and evaluation provides a robust framework for similar object detection tasks.

Feel free to explore the code, adapt it to your needs, and contribute to the project! 🐠🚀

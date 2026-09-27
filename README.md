# Industrial Defect Detection using YOLO

## Overview

This project uses deep learning and YOLO object detection to identify and localize surface defects in industrial steel images.

The model is trained on the NEU Surface Defect dataset containing six types of defects:

- Crazing
- Inclusion
- Patches
- Pitted Surface
- Rolled-in Scale
- Scratches

## Tech Stack

- Python
- YOLO
- Ultralytics
- PyTorch
- OpenCV
- Google Colab

## Methodology

1. Downloaded and extracted the NEU Surface Defect dataset
2. Prepared the dataset in YOLO format
3. Created the YOLO dataset configuration
4. Trained a YOLO model for 10 epochs
5. Evaluated the model on validation images
6. Generated predictions on unseen validation images
7. Visualized detected defects using bounding boxes and confidence scores

## Model Performance

| Metric | Score |
|---|---:|
| Precision | 0.884 |
| Recall | 0.651 |
| mAP@50 | 0.756 |
| mAP@50-95 | 0.481 |

## Sample Predictions

The trained model successfully detected multiple defect categories including patches, inclusions, pitted surfaces, and scratches in validation images.

## Project Structure

```text
industrial-defect-detection/
│
├── Industrial_Defect_Detection.ipynb
└── README.md

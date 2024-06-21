# MSOD-PT
Multiple small object detection and prioritized tracking using deep learning #yolov8
# Object Detection for Navy Rescue Operations

This project implements object detection using a custom pretrained YOLOv8 model to detect small boats, ships, and humans in Navy rescue operations. The project includes deep learning prioritized tracking, with a focus on accurately identifying and tracking these objects in challenging maritime environments. for mre details check the paper publication https://ieeexplore.ieee.org/document/10391309 


## Introduction

The goal of this project is to assist in Navy rescue operations by providing reliable object detection and tracking for small boats, ships, and humans. Using YOLOv8 for detection and a deep learning approach for prioritized tracking, this project aims to enhance situational awareness and operational efficiency during rescue missions.

## Installation

To set up the project, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/MSOD-PT.git
    cd MSOD-PT
    ```

2.  pip install all the requirements

3. Ensure you have the necessary files:
   - `detection.py`
   - `tracking.py`
   - `best_model.pth` (pretrained model)
   - `model_training.zip` (contains the training dataset and scripts)

## Usage

### Detection and Tracking

To run the object detection:

```bash
python detection.py 
python tracking.py

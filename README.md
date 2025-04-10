# Satellite Object Detection with YOLOv8

This project explores the use of **YOLOv8** for detecting objects—specifically boats—in satellite imagery. It focuses on evaluating pre-trained models in terms of inference speed and visual accuracy.

## Overview

- Utilizes **YOLOv8 pre-trained models** for fast and efficient object detection.
- Observations highlight that some boats with visible *bow waves* are not detected—likely due to dataset limitations during pre-training.
- Emphasizes the **duality of foundation models** like **DINO** (for feature extraction) and **SAM** (for segmentation).


Sam Model: https: github.com/facebookresearch/segment-anything
Pre-trained YOLO: https://huggingface.co/search/full-text?q=boat+satellite

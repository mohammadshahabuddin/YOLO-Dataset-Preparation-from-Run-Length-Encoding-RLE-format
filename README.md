# YOLO-Dataset-Preparation-from-Run-Length-Encoding-RLE-format

This repository contains a Python script for preprocessing ship detection datasets. The script converts ship mask annotations from Run-Length Encoding (RLE) format into YOLO-compatible bounding box labels. It includes functionalities for:

**Run-Length Decoding:** Converts RLE mask annotations into binary masks.

**Bounding Box Extraction:** Derives bounding boxes from binary masks.

**YOLO Format Conversion:** Normalizes bounding boxes and generates .txt label files in YOLO format.

**Batch Processing:** Processes multiple images and annotations efficiently.

# Features
Handles RLE mask decoding and combines multiple masks per image.

Extracts and normalizes bounding boxes for YOLO detection format.

Saves the labels in an organized folder structure.

# Requirements

Python

Libraries: pandas, numpy, Pillow

# Usage

Place your dataset (ship_dataset_train_v2.csv and images) in the specified folders and run the script to generate YOLO-compatible label files.
This notebook will be useful for this kind of dataset where annotations are given in Run-Length Encoding (RLE) format : https://www.kaggle.com/competitions/airbus-ship-detection/data

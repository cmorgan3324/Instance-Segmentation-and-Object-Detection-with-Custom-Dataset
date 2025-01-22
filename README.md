# Instance Segmentation and Object Detection with Custom Dataset

This repository provides an implementation of **instance segmentation and object detection** using **Mask R-CNN** with a custom dataset, utilizing the **Detectron2** framework.

## Features
- Train a pre-trained **Mask R-CNN** model on a custom dataset.
- Perform **inference and evaluation** using the trained model.
- **Visualize results** with bounding boxes and segmentation masks.

## Requirements
Ensure you have the following dependencies installed before running the notebook:
```bash
pip install detectron2 torch torchvision opencv-python matplotlib numpy
```

## Dataset Preparation
- The notebook expects a custom dataset in COCO format.
- Modify the dataset registration function to match your dataset annotations.

## Usage

1. **Import and Train the Model**
   - Load a pre-trained model from **Detectron2's Model Zoo**.
   - Configure and fine-tune it on the custom dataset.

2. **Inference & Evaluation**
   - Use the trained model to make predictions.
   - Evaluate results using COCO metrics.

## Running the Notebook
Open and run [`Instance_Segmentation_and_Object_Detection.ipynb`](Instance_Segmentation_and_Object_Detection.ipynb) step by step.

## Dependencies Imported in the Notebook
The notebook utilizes:
- **Detectron2** (for object detection and segmentation)
- **PyTorch** (for deep learning computations)
- **OpenCV** (for image processing)
- **Matplotlib** (for visualization)
- **NumPy** (for numerical operations)

## Results
Once trained, the model generates segmented object masks with bounding boxes on input images.

---
  
For any issues or improvements, feel free to contribute!

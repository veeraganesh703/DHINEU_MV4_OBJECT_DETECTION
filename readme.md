# Object Detection  (YOLOv8)

This project demonstrates an *object detection* using **YOLOv8*.  
It trains on custom datasets, applies augmentations, performs inference, and provides a simple Gradio UI for testing.

---

## Features
- *YOLOv8-based detection* (Ultralytics).
- *Data Augmentation* with Albumentations.
- *Custom Dataset Training* (train/val/test splits).
- *Inference* with pre-trained and fine-tuned weights.
- *Interactive Gradio UI* for building real-time interface 
- Export results (predictions, metrics, model weights).

---

## Project Workflow
1. *Input*: Custom dataset (images + annotations).
2. *Preprocessing*: Apply augmentations & organize train/val/test splits. [Dataset](https://drive.google.com/file/d/1xwgfQq-fBlKzyDKRtsc-JkcNuHdwVZky/view?usp=sharing)
3. *Training*: Fine-tune YOLOv8 on the dataset.
4. *Evaluation*: Monitor metrics (mAP, Precision, Recall).
5. *Inference*: Run detection on new images.
6. *UI*: Use Gradio for quick demo/testing.
7. *Output*: Predictions, annotated images, and saved weights.

---

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/veeraganesh703/DHINEU_MV4_OBJECT_DETECTION
cd DHINEU_MV4_OBJECT_DETECTION
pip install -r requirements.txt
```

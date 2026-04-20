# Camera Trap Animal Detection

## Overview

This project presents a computer vision pipeline for automated wildlife monitoring using remote sensing camera trap data. It combines temporal analysis, object detection, and deep learning-based classification.

## Key Features

* Image sequence extraction using EXIF timestamps
* Animal detection using  [MegaDetector](https://github.com/agentmorris/MegaDetector)
* Species classification using YOLOv5 and YOLOv8
* Conversion of detection outputs to YOLO annotation format

---

## 📂 Project Files

* 📓 **Notebook:** [camera_trap_pipeline.ipynb](./camera_trap_pipeline.ipynb)
* 📄 **Full Report:** [report.pdf](./report.pdf)
* 📦 **Requirements:** [requirements.txt](./requirements.txt)

---

##  Setup

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Pipeline
1. Open the notebook:

   ```bash
   jupyter notebook camera_trap_pipeline.ipynb
   ```
2. Update dataset paths inside the notebook
3. Run all cells

---

## Results

* Achieved ~85% classification accuracy (Iteration 1)
* Scaled model from 2 to 9 animal classes
* Compared performance of YOLOv5 and YOLOv8

---

##  Dataset

The dataset used in this project is not publicly available due to restrictions.

To reproduce results, you can use:

* Public datasets
* Your own camera trap images

---



# alvea-medical-imaging-suite-showcase
Technical architecture showcase of Alvéa: Automated clinical CT analysis desktop suite built with C++, Python, PyQt, SQL, and Deep Learning.
# Alvéa – Automated Clinical CT Analysis & Medical Imaging Suite (Architecture Showcase)

**Alvéa** is a desktop medical imaging application engineered with **C++, Python, PyQt, OpenCV, and SQL** for automated thoracic CT visualization, multi-organ anatomical segmentation, and pulmonary nodule detection.

> *Note: As Alvéa is an active proprietary clinical software project, this repository serves as a technical architecture showcase.*

## System Architecture & Core Capabilities
- **DICOM Volumetric Engine (`C++` / `Python`):** High-speed parsing of radiological series, Hounsfield Unit (HU) windowing, and multi-planar reconstruction (Axial, Coronal, Sagittal views).
- **Deep Learning Inference Integration (`PyTorch` / `CUDA`):** Asynchronous background execution of multi-organ segmentation (U-Net) and contextual nodule detection (YOLOv8–YOLOv12) pipelines without freezing the clinical GUI.
- **Interactive Clinical GUI (`PyQt`):** Custom viewport controls, ROI measurement tools, bounding-box/mask overlays, and automated radiological reporting.
- **Local Database Management (`SQL`):** Structured persistence for patient metadata, study history, and inference logs.

## Tech Stack
- **Languages:** Python, C++, SQL
- **GUI & Visualization:** PyQt, OpenCV, Matplotlib
- **AI / Computer Vision:** PyTorch, CUDA, Ultralytics YOLO, U-Net

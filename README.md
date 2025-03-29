# Enhanced Object Detection based on YOLOv9 for Marine Life

**Presented at CICN 2024 Conference on 23rd December**

---

## Overview

This project presents an enhanced object detection system for marine life, utilizing the YOLOv9 model to identify and classify marine species from underwater images and videos. The goal is to improve the accuracy and speed of marine life detection, which has significant applications in marine conservation, research, and monitoring ecosystems.

This repository includes the model, dataset, and code used to achieve enhanced performance for detecting marine life in real-time conditions.

---

## Table of Contents

- [Overview](#overview)
- [Conference Details](#conference-details)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [Dataset Details](#dataset-details)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

---

## Conference Details

Provide details about the conference where your project was presented.

Example:  
> - **Conference Name**: CICN 2024 (16th IEEE International Conference on Computational Intelligence and Communication Networks)  
> - **Date**: 22nd - 23rd December 2024  
> - **Location**: Oriental University, Indore, India  
> - **Paper/Project Title**: "Enhanced Object Detection based on YOLOv9 for Marine Life"  
> - [Link to conference proceedings or related papers](https://ieeexplore.ieee.org/document/10847536)

---

## Features

- High accuracy object detection for marine life species using YOLOv9.
- Real-time detection capabilities for underwater video streams.
- Support for identifying various marine species with custom training data.
- Optimized performance for edge devices in marine research.

---

## Technologies Used

- **Languages**: Python
- **Frameworks**: YOLOv9, TensorFlow, OpenCV, PyTorch
- **Libraries**: NumPy, Matplotlib, Pandas
- **Tools**: Google Colab, Git, Jupyter Notebooks

---

## Installation Instructions

Since this project is designed to run on **Google Colab**, there is no need for complex local installations. You can simply open the `.ipynb` file in Colab and run it.

### Steps:

1. **Open the Colab notebook**:
   - Download the `.ipynb` file and open it in Colab.
   
2. **Run the cells in the notebook**:
   - The notebook is already set up with all dependencies and instructions to run the object detection pipeline. You just need to execute the cells sequentially.

3. **Ensure GPU is enabled in Colab** (optional for faster execution):
   - Go to **Runtime** > **Change runtime type** > **GPU**.
   
4. **Download the pretrained YOLOv9 model** and any necessary datasets within the Colab notebook (links will be provided in the description).

---

## Dataset Details

The dataset used for training the YOLOv9 model consists of labeled underwater images and videos containing various marine species. The dataset is essential for training the model to accurately detect and classify marine life.

- **Dataset Source**: [Roboflow](https://public.roboflow.com/object-detection/aquarium)
- **Number of Images**: [e.g., 5,000+ images]
- **Number of Classes**: [e.g., 10 species, including fish, coral, etc.]
- **Image Dimensions**: [e.g., 416x416]
- **Annotations Format**: [e.g., YOLO format, Pascal VOC, etc.]

Please refer to the Colab notebook for instructions on how to download and use the dataset within the project.

---

## Contributing

We welcome contributions from the community! If you’d like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request explaining your changes.

---

## Acknowledgements

- **Authors**: [Akshat Pawar](https://github.com/akshatpawar), Ankush Handa, Madhav Pujari
- The marine life dataset was provided by [RoboFlow](https://public.roboflow.com/object-detection/aquarium).

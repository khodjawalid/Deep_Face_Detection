# Face Detection Project

### Overview

This project implements a face detection system using TensorFlow and OpenCV. The system is capable of detecting faces in real-time, leveraging deep learning techniques for accurate and efficient detection.

### Features

- Real-time face detection using OpenCV.
- Deep learning-based model trained with TensorFlow.
- Custom dataset support with image annotation.
- Image preprocessing for improved detection performance.

### Project's workflow

  1. Install dependencies, collect images using OpenCV and annotate using LabelMe.
  2. Review Dataaset and build image loading function.
  3. Partition unaugmented Data (tarin/test/validation split)
  4. Image auumentation using Albumentations.
  5. Build pipeline.
  6. Build Deep learning model using the functionnal API.
  7. Define losses and Optimizers.
  8. Train Neura Network.
  9. Make prediction (static and real time)

### Future Improvements

- Improve model accuracy with a larger and more diverse dataset.
- Optimize real-time performance for edge devices.
- Extend the system to include face recognition and emotion detection.

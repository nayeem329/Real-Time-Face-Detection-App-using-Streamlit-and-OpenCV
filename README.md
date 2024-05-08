# Real-Time Face Detection App using Streamlit and OpenCV

1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Usage Instructions](#usage-instructions)
7. [Limitations](#limitations)
8. [Contributing](#contributing)
9. [License](#license)
10. [Conclusion](#conclusion)

## Introduction
This project is a real-time face detection application built using Streamlit and OpenCV. It allows users to either open the camera and detect faces in real-time or upload an image to detect faces. The application outputs the detected faces with bounding boxes.

![img_1](https://github.com/nayeem329/Real-Time-Face-Detection-App-using-Streamlit-and-OpenCV/assets/153347543/09d0f3bb-c693-4e40-8f69-eb910ae40b78)


## Features
- Real-time face detection using webcam
- Upload an image and detect faces
- User-friendly interface built with Streamlit
- Supports popular image formats: JPG, JPEG, PNG

## Requirements
- Python 3.x
- OpenCV
- Streamlit

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nayeem329/real-time-face-detection.git
2. Install the required Python packages:
```bash
pip install -r requirements.txt
```
# Usage
1.Run the Streamlit app:
```bash

streamlit run main.py
```
2.Access the application in your web browser by navigating to the URL provided in the terminal output.
# Usage Instructions
- To detect faces in real-time, click on "Open Camera".
- To detect faces in an uploaded image, click on "Upload an image" and either browse your files or drag and drop an image file. Supported formats are JPG, JPEG, and PNG.
# Limitations
- The face detection accuracy may vary based on factors like lighting conditions and image quality.
- Large image files may take longer to process.
# Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create your feature branch: git checkout -b feature-name.
3. Commit your changes: git commit -m 'Add some feature'.
4. Push to the branch: git push origin feature-name.
5. Submit a pull request.
# License
This project is licensed under the MIT License.

# Conclusion
This project provides a simple yet effective solution for real-time face detection. By leveraging Streamlit for the user interface and OpenCV for computer vision tasks, the application offers a seamless experience for detecting faces either from a live camera feed or uploaded images. With further enhancements and contributions from the community, it has the potential to evolve into a versatile tool for various face detection applications.

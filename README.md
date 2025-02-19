# Face and Eye Detection Using OpenCV

## Overview
This project implements **face and eye detection** using **OpenCV’s Haar cascade classifiers**. The model detects human faces and eyes in images and highlights them with bounding boxes.

## Features
- ✅ Detects faces in images
- ✅ Detects eyes in images
- ✅ Uses **Haar cascade classifiers** for detection
- ✅ Works in **Google Colab**

## How It Works
1. Converts an image to grayscale.
2. Uses **pre-trained Haar cascade models** (`haarcascade_frontalface_default.xml` and `haarcascade_eye.xml`).
3. Detects faces and eyes.
4. Draws bounding boxes around detected regions.
5. Displays the final image.

## Installation
To use this project in Google Colab:
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/face-detection-opencv.git
   cd face-detection-opencv
   ```
2. Open **Google Colab** and run the notebook.

## Usage
1. Upload the required **Haar cascade XML files**:
   - [haarcascade_frontalface_default.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
   - [haarcascade_eye.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_eye.xml)

2. Run the detection functions in **Google Colab**:
   ```python
   face_detect("path_to_image.jpg")
   eye_detect("path_to_image.jpg")
   ```

## Example Output
Here’s an example of face detection in action:

1. Face Detection Output

![Face Detection Output](readme_images/face.jpg)

2. Eye Detection Output

![Eye Detection Output](readme_images/eye.jpg)

## Applications
- 🔹 **Security Systems** - Face recognition in surveillance
- 🔹 **Biometric Authentication** - Used in smartphones
- 🔹 **Medical Imaging** - Detecting facial features for diagnosis
- 🔹 **AI & AR** - Used in Snapchat filters, virtual makeup apps

## Future Enhancements
- Improve detection accuracy using **Deep Learning (CNNs)**
- Implement **real-time face detection** using a webcam
- Add **gender and age prediction**

---

🚀 **Happy Coding!** 🚀

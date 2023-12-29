# Face and Happiness Detection

This project combines two facial recognition applications: one for detecting faces and eyes, and the other for detecting happiness by identifying smiles. The implementation is based on the OpenCV library in Python.

## Prerequisites

Before running the code, ensure you have the following dependencies installed:

- Python
- OpenCV

You can install OpenCV using:

```bash
pip install opencv-python
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/ithurtzwhenip/Face-and-Smile-detector.git
cd Face-and-Smile-detector
```

2. Download the required Haar cascades:

   - [haarcascade_frontalface_default.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
   - [haarcascade_eye.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_eye.xml)
   - [haarcascade_smile.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_smile.xml)

   Place these XML files in the project directory.

3. Run the face and eye detection:

```bash
python face-detection.py
```

4. Run the happiness detection:

```bash
python smile_detector.py
```

Press 'q' to exit the video stream.

## Explanation

- `face-detection.py`: Detects faces and eyes using Haar cascades.
- `smile-detector.py`: Extends face detection to identify smiles.

The Haar cascades used for face, eye, and smile detection are included in the OpenCV library.

## Acknowledgments

- [OpenCV](https://opencv.org/): Open Source Computer Vision Library.

Feel free to contribute or report issues!

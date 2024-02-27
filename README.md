# Snap-Filter-with-Facial-Landmarks-Detection

## Overview
This repository contains the implementation of a Snap Filter using facial landmarks detection. The Snap Filter applies various fun effects and overlays to faces detected in images or video streams. It utilizes the MediaPipe library for facial landmarks detection, enabling the accurate placement of filters on faces.

## Features
- Facial Landmarks Detection: Utilizes MediaPipe's facial landmarks detection to accurately locate key points on detected faces.
- Snap Filters: Applies a variety of fun filters and overlays on faces, enhancing images or video streams with creative effects.
- Real-time Application: Can be used in real-time with a webcam feed, allowing users to interact with the filters instantly.
- Customizable: Users can modify and create their own filters by leveraging the facial landmarks provided by the MediaPipe library.

## Installation
1. Install Jupyter Notebook:
    - If you haven't already installed Jupyter Notebook, you can do so using pip, which is the Python package manager:
      pip install notebook
2. Download the Jupyter Notebook File:
    - Download the snapFilter.ipynb file of the Snap filter project from the repository.
    - You will also need some test images. You can use your own images, just change the image paths.
3. Open Jupyter Notebook:
    - Navigate to the directory where you downloaded the snapFilter.ipynb file.
    - Start Jupyter Notebook by running the following command in your terminal: jupyter notebook
4. Access the Notebook:
    - Once Jupyter Notebook server starts, it will open in your default web browser.
    - Click on the snapFilter.ipynb file of the Snap filter project to open it in the Jupyter Notebook interface.
6. Run the Notebook:
    - You can now run the code cells within the notebook by clicking on them and pressing Shift + Enter.

## Usage
1. Run the script snap_filter.py:
python snap_filter.py
2. Follow the on-screen instructions to either use the Snap Filter with images or video streams.
3. Enjoy experimenting with different filters and effects on detected faces!

## Supported Filters
- Glasses Overlay: Adds various styles of glasses over the eyes.
- Hat Overlay: Places different types of hats on the head.
- Animal Ears: Attaches cute animal ears to the head.
- Facial Distortions: Applies funny facial distortions and effects.

## Contributions
Contributions are welcome! If you have any ideas for additional filters, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## Acknowledgements
- [MediaPipe](https://developers.google.com/mediapipe) for providing powerful tools for face detection and facial landmarks detection.
- [OpenCV](https://opencv.org/) for image and video processing capabilities.
- [matplotlib](https://matplotlib.org/) for visualizing images and results.
- [NumPy](https://numpy.org/) for numerical computations.

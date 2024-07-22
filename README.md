# Image Stitching Project
Please read the [problem_statement.md](problem_statement.md) file for questions and more clarity.

This project involves stitching two pairs of images to create panoramic or wide images. Two approaches are used for stitching:

1. **Using OpenCV's Built-in Function**: The `cv2.createStitcher()` function is utilized for automatic image stitching.
2. **Custom Code**: A custom implementation of the stitching pipeline using feature detection, matching, and homography estimation.

## Features

- **Feature Detection**: Utilizes SIFT, ORB, and BRISK algorithms.
- **Feature Matching**: Employs brute-force matching.
- **Homography Estimation**: Uses the RANSAC algorithm for robust estimation.
- **Blending**: Evaluates stitching quality and blending techniques.

## Setup

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd <repository-directory>

2. **Install Dependencies**

   Ensure you have Python installed. You can create a virtual environment and install the required Python packages using:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   pip install -r requirements.txt
   
3. **Run the Image Stitching**
   - Using the Built-in OpenCV Function
   - Using the Custom Code 

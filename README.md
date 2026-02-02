Shape Recognition App (MATLAB Computer Vision Project)

## Overview
This project is an interactive MATLAB-based computer vision application for detecting
and classifying geometric shapes in digital images using image processing techniques.

The app allows users to load images, configure preprocessing parameters, and visualize
detected shapes with multiple overlays.

## Key Features
1. Multi-shape detection (circles, stars, polygons, etc.)
2. Adaptive & global thresholding
3. Edge-based detection for outline shapes
4. Watershed segmentation for touching objects
5. Interactive visualization with contours, bounding boxes, and labels

## Project Structure
- Preprocessing & Noise Reduction
- Image Segmentation (Adaptive / Global Threshold / Edge Detection)
- Feature Extraction (Area, Circularity, Solidity, etc.)
- Rule-based Shape Classification
- Interactive Visualization & Export


## How to Run
1. Ensure MATLAB path includes the project folder
2. Run:
   ShapeRecognitionApp
3. Or upload and run directly on MATLAB Online

## How to Use
1. Click **Load Image** to import an image
2. Choose preprocessing method:
   - Adaptive (default)
   - Global Threshold
   - Edge Detection
3. Adjust sliders:
   - Threshold
   - Min / Max Area
   - Circularity / Solidity
4. Click **Detect Shapes**
5. Toggle visualization options:
   - Contours
   - Bounding Boxes
   - Labels
   - Fill & Transparency

## Troubleshooting
- Too much noise → Increase Min Area
- Shapes merged → Use Edge Detection or adjust Threshold
- Wrong classification → Tune Circularity / Solidity
- Dark background → Enable Invert Image

## Requirements
- MATLAB R2021a or later
- Image Processing Toolbox

## Documentation
See:
- README.pdf for project overview
- User_Guide.pdf for detailed usage instructions

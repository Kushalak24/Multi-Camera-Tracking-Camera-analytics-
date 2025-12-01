# README

## Group Members

- Aaryan Reddy Kotha (SE22UCAM001)
- Kushala Kusumba (SE22UCSE148)

## How to Run the Code

1. **Install Required Packages**

   Run the following command to install all required dependencies:
   pip install kagglehub ultralytics deep_sort_realtime opencv-python tqdm numpy matplotlib pandas scikit-learn torch

2. **Input Files Needed**

Ensure the following files and folders are present in the project directory:
- `Wildtrack/Image_subsets/` : Contains all camera image folders (C1 to C7).
- `Wildtrack/calibrations/` : Contains intrinsic and extrinsic calibration XML files for every camera.
- `Wildtrack/annotations_positions/` : Contains JSON annotation files for each frame.

The data can be downloaded automatically with:
import kagglehub
path = kagglehub.dataset_download("mrriandmstique/wildtrack-multi-camera-tracking")


3. **Run the Script**

Run the Python script or notebook provided. Follow any in-line instructions and ensure all folders above are available in the correct structure. The code will preprocess files, perform detection and tracking, and create output and evaluation files in the project directory.


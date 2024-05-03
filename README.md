# Voxel-Based 3D Reconstruction
![alt text](https://github.com/aalexa201222/Voxel-based-3D-reconstruction/blob/dfde0d2bd96b0f4fb716dd5719a7691113896738/flow.png?raw=true)

## Overview
This project focuses on 3D reconstruction using a multi-camera setup to calibrate and generate voxel-based models of dynamic scenes. The primary goals include calibrating camera intrinsics and extrinsics, performing background subtraction, and implementing a silhouette-based voxel reconstruction algorithm. This project is part of an advanced course in computer vision, emphasizing practical implementation of theoretical concepts.

## Key Features
- **Multi-Camera Calibration**: Calibration of four cameras using chessboard patterns to accurately determine both intrinsic and extrinsic parameters.
- **Background Subtraction**: Implementation of an advanced background subtraction technique to isolate the subject from the background efficiently, enhancing the clarity of the resulting voxel model.
- **Voxel Reconstruction**: Utilization of silhouette data from multiple cameras to reconstruct a 3D voxel model of the observed scene, focusing on accuracy and computational efficiency.

## Requirements
- **OpenCV**: Used for all image processing and camera calibration tasks.
- **Python 3.8+**: Required for running the provided scripts and managing data processing.
- **NumPy**: Essential for handling large datasets and matrix operations integral to 3D reconstruction.


## Installation
Clone the repository to your local machine:
git clone https://github.com/aalexa201222/Camera-geometric-calibration.git

## Contributors
[Andreas Alexandrou](https://www.linkedin.com/in/andreas-alexandrou-056528242) <br />
Sotiris Zenios

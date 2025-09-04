# Photometric Stereo Assignment
Computer Vision (CSCI 49369) Photometric Stereo Assignment. No code in this repo.
## Overview  
This project applies **photometric stereo** to estimate object surface properties from multiple grayscale images captured under different lighting conditions. The program reconstructs:  
- **Surface normals** to describe object geometry  
- **Albedo maps** to represent surface reflectance  

## Approach  
- **Image preprocessing:** Thresholded input images to identify object boundaries and compute basic geometry (center, radius).  
- **Light estimation:** Determined light source directions from calibration sphere images.  
- **Surface reconstruction:** Used linear algebra (matrix inversion) to solve for per-pixel surface normals and albedo.  
- **Visualization:** Generated output images showing surface orientations (needle plots) and reflectance maps.  

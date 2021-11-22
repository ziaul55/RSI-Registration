# WSI Registration

## Keypoint Detection

## Dependencies and Environment
The codes are developed and tested in MATLAB R2020a, with both OpenCV.3.4.1 and the VLFeat open-source libraries on a desktop computer with Intel(R) Core (TM) i7-3770 CPU @ 3.40 GHz, 12.00GB RAM, running the Windows 8.1. In order to use the codes, you need some prerequisite as follow: 
- 	MATLAB 2020a
- 	OpenCV (3.4.1)
- 	VLFeat 0.9.21 

you also need the required build tools for windows which is Visual Studio. Please see https://github.com/kyamagu/mexopencv to how to download and install OpenCV on your MATLAB software. Also, please see the https://www.vlfeat.org/ to how to download and install VLFeat 0.9.21.

Getting Started
After installing OpenCV 3.4.1 and VLFeat 0.9.21, it is enough to use only main.m for a quick start. Here are one examples.

More configuration items for detector-descriptors can be found in functions SiftDetector.m (SIFT), SurfDetector.m (SURF), and feature_detector.m for (KAZE, AKAZE, ORB, SURF). The metrics (RMSE and NTG) are also provided in the score_index.m. Furthermore, RCS_Regression.m is a function for selecting RCS from matches and RRN modeling. In addition, appendimages.m is used for visualition matches and TIN-basedLocalAffine.m is program of TIN-based local affine for blunder rejection from matches.    

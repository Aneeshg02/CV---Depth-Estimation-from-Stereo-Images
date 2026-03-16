# CV---Depth-Estimation-from-Stereo-Images

## Description
This project focuses on estimating scene depth from stereo image pairs, a fundamental problem in computer vision with applications in autonomous driving, robotics, and 3D scene understanding. The project uses the KITTI stereo dataset and implements classical stereo matching algorithms, including StereoBM and StereoSGBM from OpenCV, to compute disparity maps from left and right camera images. The predicted disparities are evaluated against ground truth using RMSE, MAE, and Bad Pixel Error (>3px) metrics to compare performance and analyze the accuracy of different depth estimation methods.

## Dataset
The project uses the KITTI Stereo Dataset, which contains stereo image pairs and ground-truth disparity maps for evaluating depth estimation algorithms.
Steps to install dataset
1. open The KITTI Vision Benchmark Suite ([Dataset download link](https://www.cvlibs.net/datasets/kitti/eval_stereo.php))
2. Select Stereo 2015 dataset.
3. Download stereo 2015/flow 2015/scene flow 2015 data set(Login to download the dataset).
4. Added some testing and training images in main branch.

## Installation
git clone https://github.com/yourusername/stereo-depth-estimation.git
cd stereo-depth-estimation

## Install required libraries
pip install opencv-python numpy matplotlib scikit-learn torch

## How to Run
1. Open juypter notebook.
2. Oopen source code(CV_project.ipynb).
3. BASE_PATH = "Choose your dataset path".
4. Run the every cell.




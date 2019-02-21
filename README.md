# training-course_hw1
Localize &amp; Correct License Plate <br>
Use to detect and locate the license plate in images.

## Dataset
* Subset of CCPD
* Only 1 licese plate in each image

## Structure
* ccpd5000
  * train (4000)
  * valid (1000)
  * test  (1000)
* log
  * (files of train & valid images' visualization)
    * metrics.jpg (Visualization of MAE & MSE) 
  * result
    * (files of test images' visualization)
    * a csv for corner detection

## How To
* open training-course_hw1.ipynb with jupyter notebook and run the code.

## Environment
* Python 3.6
* Pytorch 1.0.0
* torchvision 0.2.1
* scikit-image 0.14.1
* tqdm 4.29.0

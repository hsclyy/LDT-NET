## LDT-NET  A Lightweight Skeleton-based Action Recognition Network via Depthwise Separable Convolutions
A  Lightweight Skeleton-based Action Recognition Network via Depthwise Separable Convolutions
Code for the paper LDT-NET：A Lightweight Skeleton-based Action Recognition Network via Depthwise Separable Convolutions.

## Installation
This code has been tested on Window10 with Keras==2.1.4 and tensorflow==1.14.0 on CPU. 
This code has been tested on Ubuntu16.04 with Keras==2.1.4 and tensorflow-gpu == 1.80 on GTX1080ti (CUDA version == 9.0.176  CUDNN version == 7501)

* building virtual environment by conda `conda create -n test_LDT-NET python=3.6`
* Install tensorflow by running`pip install tensorflow==1.14.0` / `pip install  tensorflow-gpu == 1.80`
* Install keras by running `pip install keras==2.1.4`.
* Install panda by running `pip install panda`.
* Install matplotlib by running`pip install matplotlib`.
* Install tqdm by running `pip install tqdm`.
* Install sklearn by running `pip install sklearn`.
* Install jupyter by running  `pip install jupyter`.

## Test JHMDB datasets:
* 1. Run  `/JHMDB/LDT-NET_JHMDB.ipynb` ( By using the preprocessed JHMDB data in /data/JHMDB)

or
* 1. Download JHMDB dataset，from http://jhmdb.is.tue.mpg.de/challenge/JHMDB/datasets  

* 2. Using `jhmdb_data_preprocessing.ipynb` to preprocess JHMDB raw data.

* 3. Run  `/JHMDB/LDT-NET_JHMDB.ipynb` 
## Test SHREC datasets:
* 1.Run `/SHREC/LDT-Net_SHREC_14-class`（By using the preprocessed JHMDB data in /data/JHMDB）

or

* 1.Download SHREC dataset from 
http://www-rech.telecom-lille.fr/shrec2017-hand/  or   
https://drive.google.com/file/d/1H_-ByZMnLTXvrUzx6XZEuPy7rxX0XENB/view?usp=sharing 

* 2.Using `SHREC_data_preprocessing.ipynb` to preprocess SHREC data.

* 3.Run `/SHREC/LDT-Net_SHREC_14-class.ipynb`

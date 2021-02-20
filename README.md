# Overview

## *LBPH -> Local Binary Patterns Histogram*

It is based on local binary operator. It is widely used in facial recognition due to its computational simplicity and discriminative power. 

**It is very efficient texture operator which labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.**
The steps involved to achieve this are:

* creating dataset
* face acquisition
* feature extraction
* classification

The LBPH algorithm is a part of opencv.


# Dependencies

    pip install numpy
    pip install opencv-python
    pip install opencv-contrib-python
 
# Quick-Start

- Fork the repository
>click on the uppermost button <img src="https://github.com/Vinamrata1086/Face-X/blob/master/Recognition-Algorithms/Facial%20Recognition%20using%20LBPH/images/fork.png" width=50>

1. **Create virtual environment**

```bash
python -m venv env
``` 

2. **Linux**
```
source env/bin/activate
```

### OR

2. **Windows**
```bash
env\Scripts\activate
```

- Clone the repository using-
```
git clone https://github.com/akshitagupta15june/LBPH-Face-Recognition.git
```

- Install Dependencies

- Execute -

#### face images samples collection

      python recognition-part-1.py 
      
#### model training + final recognition

      python recognition-part-2.py 


Note: Make sure you have haarcascade_frontalface_default.xml file 


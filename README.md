# Openpose project 

This project is used for estimate the human skeletons resulting image and joint coordinates (csv file), where they were modified from https://github.com/ildoonet/tf-pose-estimation


# Installation

Download and install python libraries
```
$ git clone https://github.com/sornsook/openpose_project
$ cd openpose_project
$ pip install -r requirements.txt
```

Install swig
```
$ apt-get update
$ apt-get install swig
$ cd tf_pose/pafprocess/
$ swig -python -c++ pafprocess.i && python3 setup.py build_ext --inplace
```

**FYI:Please note that this code is run by Tensorflow 2.x and Python 3.x**


# FaceDetection

After downloading this project, the following steps you have to do:

### 1. Get Classifiers

```bash
cd FaceDetection
cd Source

# Get Eyes Classifier
wget https://raw.githubusercontent.com/opencv/opencv/master/data/haarcascades/haarcascade_eye_tree_eyeglasses.xml

# Get Face Classifier
wget https://raw.githubusercontent.com/opencv/opencv/master/data/haarcascades/haarcascade_frontalface_default.xml
```

### 2. Compile and Execute

```bash
## Compile
g++ FaceDtection.cpp -o output `pkg-config --cflags --libs opencv`

## Execute
./output
```

> If you hadn't installed opencv on your computer yet, you can see my [article](https://wenyuangg.github.io/opencv/installation/2017/12/25/opencv-installation.html) to install

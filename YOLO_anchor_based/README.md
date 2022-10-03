# YOLO
YOLO is an extremely fast real time multi object detection algorithm. In this project, I use 10K street scene images with correponding labels as training data. The image dimension is 128x128x3, and the labels include the semantic class and the bounding box corresponding to each object in the image.


## Network architecture
![](images/Network_Architecture.png)

## Loss Objective
![](images/loss.png)

## Results 

### Ground Truth Image
![](images/1.png)

### Raw Output from the Network (PreNMS)
![](images/6.png)

### After Post Processing
![](images/7.png)

### Visual inspection of Performance
![](images/9.png)

### Loss Plots
![](images/3.png)

### Average Precision
![](images/5.png)



# PointsClassifier

Machine Learning: OpenCV Points Classifier Demo

(https://github.com/Itseez/opencv/blob/master/samples/cpp/points_classifier.cpp)

## Compile:

```shell
$ gcv points_classifier.cpp points_classifier
```

### Note:

gcv alias in '~/.bashrc':
'
```shell
gcv () { g++ -std=c++11 `pkg-config --cflags opencv` "$1" `pkg-config --libs opencv` -o "$2";}
```

### Run

```shell
$ gcv points_classifier.cpp points_classifier
$ ls
points_classifier  points_classifier.cpp
$ ./points_classifier 
Use:
  key '0' .. '1' - switch to class #n
  left mouse button - to add new point;
  key 'r' - to run the ML model;
  key 'i' - to init (clear) the data.

init done 
opengl support available 

```

### Input Data point:

![screenshot0](points_002.png)

## Screenshots:

### Artificial Neural Network

![screenshot1](ANN_004.png)

### ADA Boost

![screenshot2](BT_006.png)

### Support Vectors Machine (C = 1)

![screenshot3](classificationSVM1_009.png)

### Support Vectors Machine (C = 10)

![screenshot4](classificationSVM2_008.png)

### Decision tree

![screenshot5](DT_007.png)

### Expectation maximization

![screenshot6](EM_003.png)

### k nearest neighbors (KNN) classifier (k = 3)

![screenshot6](kNN2_010.png)

### k nearest neighbors (KNN) classifier (k = 15)

![screenshot6](kNN_011.png)

### Normal Bayes Classifier

![screenshot6](NormalBayesClassifier_012.png)


"**A
computer
program
is
said
to
learn
from
experience
E
with
respect
to
some
task
T
and
some
performance
measure
P,
if
its
performance
on
T,
as
measured
by
P,
improves
with
experience
E.**" - Tom Mitchell

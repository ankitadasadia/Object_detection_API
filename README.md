# Object_detection_API

The purpose of this repository is to show object detection classifier using Tensorflow object detection API. For this classifier, I ahve six different objects I want to detect.
Therefore, First, I set environment and install all essential packages. For this project, I use Tensorflow 1.15 and python 3.6.

Then, I gathered images using google platform and annotate them and give label to each images using Label Image tools in order to convert into Tfrecords. Apparently,
I train model on googal colab as it is fast and efficient for large dataset. Accordingly, generate frozen inference_graph to check output of classsifer. This classifier can be
evalute using image, video and webcame.

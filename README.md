`WORK IN PROGRESS`

# LFW-Evaluation
 Evaluation of Labeled Faces in the Wild (LFW Face Database).

Solving problem as embedding problem:
~~~

1. "Learning a Similarity Metric Discriminatively, with Application to Face Verification"
http://yann.lecun.com/exdb/publis/pdf/chopra-05.pdf

2. "Deep Face Recognition"
http://www.robots.ox.ac.uk/~vgg/publications/2015/Parkhi15/parkhi15.pdf
~~~

Solving problem as multiclass classification problem:
~~~

1. "Naive-Deep Face Recognition: Touching the Limit of LFW Benchmark or Not?"
https://arxiv.org/pdf/1501.04690v1.pdf

2. "Deep Learning Face Representation from Predicting 10,000 Classes"
http://mmlab.ie.cuhk.edu.hk/pdf/YiSun_CVPR14.pdf

3. "Deep Face Recognition"
http://www.robots.ox.ac.uk/~vgg/publications/2015/Parkhi15/parkhi15.pdf

4. "A Discriminative Feature Learning Approach for Deep Face Recognition" [softmax loss + center loss]
http://ydwen.github.io/papers/WenECCV16.pdf
~~~

Datasets:
~~~
http://www.vision.caltech.edu/Image_Datasets/Caltech_10K_WebFaces/
http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
http://vision.seas.harvard.edu/pubfig83/
http://www.robots.ox.ac.uk/~vgg/data/vgg_face/
https://www.microsoft.com/en-us/research/project/ms-celeb-1m-challenge-recognizing-one-million-celebrities-real-world/

https://www.cs.tau.ac.il/~wolf/ytfaces/
~~~

Code:
~~~
Tensorflow:
https://github.com/davidsandberg/facenet

Caffe:
https://github.com/happynear/FaceVerification
https://github.com/ydwen/caffe-face
https://github.com/AlfredXiangWu/face_verification_experiment
~~~

TODO:
~~~
Rework this sklearn example 
http://scikit-learn.org/stable/auto_examples/applications/face_recognition.html

Help for parsing
https://github.com/scikit-learn/scikit-learn/blob/master/sklearn/datasets/lfw.py
~~~

Other:
~~~
http://www.briancbecker.com/blog/research/pubfig83-lfw-dataset/

Fisher Vector Face
https://www.robots.ox.ac.uk/~vgg/software/face_desc/

http://cmusatyalab.github.io/openface/models-and-accuracies/
http://www.robots.ox.ac.uk/~vgg/software/vgg_face/
~~~

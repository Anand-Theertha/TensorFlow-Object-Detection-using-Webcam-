# Hand gestures detection using Webcam (TensorFlow Object Detection API)

#### The project preforms live time object detection using the webcam and classifies the hand gestures into four different classes: Livelong, ThumbsUp, ThumbsDown and Peace. 

The webcam captures images at fixed intervals of time for training dataset for each class using the [LabelImg](https://github.com/tzutalin/labelImg) tool. Tensorflow Object Detection API is installed to work both locally as well as on Google Colab. A pre-trained model (ssd_mobilenet_v2_fpnlite_320x320_coco17_tpu-8) is modified to label the hand gestures trained into the model. The preformance matrix of our model is evaluated: __Average Precision - 78% and Average Recall - 79%__ with 10 images to train for each class. 

Output seen on Colab when model is tested using an image - 
![colab-2](https://user-images.githubusercontent.com/54447234/136154485-05c8305c-6246-4c93-baa8-5cf96921b368.PNG)

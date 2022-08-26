# Fruit Ripeness Detection React Application

This app can be used for real time object detection by leveraging [TensorFlow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection), [React](https://reactjs.org/), [Tensorflow JS](https://www.tensorflow.org/js) and [IBM Cloud](https://www.ibm.com/cloud). This repository contains the code and [Google Colab notebook](https://github.com/xzong0619/Fruit-Ripeness-Detection/blob/main/Banana_ripeness_training.ipynb) for training a detector of banana ripeness.

### Problem Statement
The model is used to detect the ripeness process of bananas. Images used for training and test are taken from [Roboflow](https://universe.roboflow.com/fruit-ripening/fruit-ripening-process/dataset/2). There are 5.3K images for training and 757 images for test.

The corresponding labels are:

- Freshripe
- Freshunripe
- Overripe
- Ripe
- Rotten
- Unripe

### Model output examples
![freshunripe](https://github.com/xzong0619/Fruit-Ripeness-Detection/blob/main/images_for_readme/test_freshunripe.png)
![ripe](https://github.com/xzong0619/Fruit-Ripeness-Detection/blob/main/images_for_readme/test_ripe.png)

### Live web app detection

- Test image from web app

![web_app](https://github.com/xzong0619/Fruit-Ripeness-Detection/blob/main/images_for_readme/web_app.jpg)

### Lessons learned
- Input image complexity
  In some of the training images, it's difficult to distinguish different stages of banana ripeness. Data augmentation process needs to be improved to consider more cases and improve the model detection accuracy.



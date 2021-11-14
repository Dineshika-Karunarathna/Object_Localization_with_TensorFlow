# Object_Localization_with_TensorFlow
(Self guided project on Coursera)
- Create synthetic data for model training
- Create and train a multi output neural network to perform object localization
- Create custom metrics and calbacks in Keras
- Showcase this hands-on experience in an interview

This project is on creating and training an Object Localization model with TensorFlow. IHere TensorFlow's Keras API is used to create a convolutional neural network which will be trained to classify as well as localize emojis in images. Localization, in this context, means the position of the emojis in the images. This means that the network will have one input and two outputs. It's much more like a simpler version of Object Detection. In Object Detection, we might have multiple objects in the input images, and an object detection model predicts the classes as well as bounding boxes for all of those objects. In Object Localization, we are working with the assumption that there is just one object in any given image, and our CNN model will classify and localize that object.

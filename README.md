# Image Classification - Deep Learning
Image Classification Project with Convolutional Neural Networks

In this project, I developed multiple multiclass image classification models applying modern Deep Learning techniques. The goal is to evaluate different approaches and test their impact on accuracy on a real-world dataset provided by Intel, consisting of over 17,000 images of landscapes and urban scenes.

The workflow includes:

* A base convolutional neural network (CNN) model.
* An extended model with additional layers and hyperparameter tuning using keras_tuner.
* A transfer learning model with VGG16, followed by fine-tuning to fine-tune the deep layers of the pre-trained model.
* A model based on data augmentation techniques (ImageDataGenerator) to improve generalization.

I used best practices such as cross-validation with validation_split, early stopping, and the use of flow_from_directory to avoid memory overload. All models were evaluated on an independent test set (seg_test), achieving a maximum accuracy of 85% with the data augmentation model. This exercise not only helped me consolidate some of the concepts learned during my Master's degree in AI, but also produced a complete, reproducible, and scalable workflow as part of my professional portfolio as a future AI engineer.

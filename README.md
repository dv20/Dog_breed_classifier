
# Dog Breed classifer using CNN

This article covers different methods to classify images of dogs according to their breed using Convolutional Neural Network (CNN). The target is to achieve as high accuracy as possible. Please find the article at https://dogbreedclassifer.blogspot.com/


## Motivation

This project aims to build convolutional neural networks (CNN) to classify breeds of dogs. CNN is often used in image classification because of its ability to develop a two-dimensional image's internal representation. This allows the model to learn the position and scale-invariant structures in the data, which is essential when working with images. We built a CNN from scratch and used existing famous CNNs like VGG16 and Resnet50. Apart from finding the corresponding dog breed, the model will give the most similar dog breed to the human face if the human image is passed.
## Used Libraries

Numpy 
Sklearn
Keras
Matplotlib
OpenCv



## Files

dog_app.ipynb: Jupyter notebook containing implementation to classify breeds of dogs.

weights.best.from_scratch.hdf5, weights.best.VGG16.hdf5, weights.best.Resnet50.hdf5: Weight of the CNN model build from scratch, and CNN model via transfer learning utilizing VGG16 and Resnet50 architecture.

images('Barbet.jpg','dog.jpg', 'dog_2.jpg', 'keenu.jpg', 'man.jpg', 'fp.jpg'): Image files used for manual testing.

DogVGG16Data.npz, DogResnet50Data.npz: Bottleneck features files for VGG16 and Resnet50.
## Conclusion

This article discussed different techniques (like Vgg16 and Resnet50) to classify dog and human images into different dog breeds. By the end, we achieved a good accuracy of 83.13%. Although it performs well, we can still do a few things to improve the performance further.

Increase the size of the data set with more dog pictures.

The number of categories (breeds) also need to be increased to cover more dogs and predict them accurately.

The labels could be improved as well.

Different Hyper-Parameters can also help to improve.

## Acknowledgement

The Udacity Data Scientist Nanodegree course initiates the project and provides part of the codes of the project.

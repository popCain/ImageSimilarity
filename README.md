# ImageSimilarity
Find similar images in dataset for a new image using **`Resnet50+KNN`**. In order to solve `curse of dimensionality` using PCA to reduce the dimensionality of features.
![](https://github.com/popCain/ImageSimilarity/blob/main/image/resnet50_knn.png)
## Resnet50(trained on imageNet)
1. Create Resnet50 from keras without toplayer to get convolutional features(2048 dimension) as output instead of the image classification probability.  
2. Extract the convolutional features for every images of dataset( Feature_size:[number_images, 2048] ).

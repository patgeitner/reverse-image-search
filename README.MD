# Reverse Image Searching

Using the pre-trained ResNet50 Convolutional Neural Network and a CalTech dataset of different images in 101 categories found [HERE](http://www.vision.caltech.edu/Image_Datasets/Caltech101/) to train a K-Nearest Neighbors model for image similarity search. The top layer of the ResNet50 model was stripped off to extract feature vectors for all of the images in the dataset and K-Nearest Neighbors was used to find the images whose feature embeddings were closest to the given image.

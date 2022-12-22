# Reverse Image Searching

Using a pre-trained ResNet50 CNN and the CalTech image dataset containing images from 101 categories [HERE](http://www.vision.caltech.edu/Image_Datasets/Caltech101/), we stripped the classification head from the ResNet model to output the final feature vectors for each of the images. We then used K-Nearest Neighbors to retrieve the closest to an input image in the feature space. We show that this is a simple, but effective way of performing reverse image search.

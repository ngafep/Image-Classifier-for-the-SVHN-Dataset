# Image Classifier for the Street View House Numbers (SVHN) Dataset
This notebook project creates a neural network that classifies real-world images of digits. It utilizes concepts such as training, testing, validating, and saving a TensorFlow classifier model.


For this project, we use the [SVHN dataset](http://ufldl.stanford.edu/housenumbers/). This is an  image dataset of over 600,000 digit images in all, and is a harder dataset than MNIST as the numbers appear in the context of natural scene images. SVHN is obtained from house numbers in Google Street View images. 

* Y. Netzer, T. Wang, A. Coates, A. Bissacco, B. Wu and A. Y. Ng. "Reading Digits in Natural Images with Unsupervised Feature Learning". NIPS Workshop on Deep Learning and Unsupervised Feature Learning, 2011.

The train and test datasets needed for this project can be downloaded from the following links:
* [Train Dataset](http://ufldl.stanford.edu/housenumbers/train.tar.gz)
* [Test Dataset](http://ufldl.stanford.edu/housenumbers/test.tar.gz)

After the files are downloaded and unzipped, two files will be found: train_32x32.mat and test_32x32.mat. These files should be saved in your Google Drive for use in the Colab notebook.

The goal is to develop an end-to-end workflow for building, training, validating, evaluating and saving a neural network that classifies a real-world image into one of ten classes.

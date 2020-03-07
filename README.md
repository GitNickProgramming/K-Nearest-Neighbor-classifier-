# K-Nearest-Neighbor-classifier
---
## Nick Gagliardi
### CS 3120
### Machine Learning - Spring 2020
---
### I. Introduction to "Animals" Dataset
### II. A Basic Image Preprocessor
### III. Building an Image Loader
### IV. k-NN: A Simple Classifier
### V. Implementing k-NN
1. Gather our Dataset:
    - The animals dataset consists of 3,000 images with 1,000 images per dog, cat, and panda class, respectively.
    - Each image is represented in the RGB color space.
    - We will preprocess each imae by resizing it to 32 x 32 pixels.
    - Taking into account the three RGB channels, the resized image dimensions imply that each image in the dataset is represented by 32 x 32 x 3 = 3,072 integers
2. Split the Dataset:
    - For this simple example, we'll be using *two* splits of the data.
    - One split for training, and the other for testing.
    - We will leave out the validation set for hyperparameter tuning and leave this as an exercise to the reader.
3. Train the Classifier:
    - Our k-NN Classifier will be trained on the raw pixel intensities of the images in the training set.
4. Evaluate:
    - Once our k-NN classifier is trained, we can evaluate performance on the test set.
### VI. k-NN Results
### VII. Pros and Cons of k-NN
### VIII. Summary

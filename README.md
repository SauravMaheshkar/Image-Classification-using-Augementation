![Alt Text](https://github.com/psych0man/Image-Classification-using-Augementation/blob/master/TF.jpg)

# Image Classification using Augmentation

![Alt Text](https://github.com/psych0man/Image-Classification-using-Augementation/blob/master/Banner.png)


# Table of contents

- [Project Title](#project-title)
- [Table of contents](#table-of-contents)
- [Overview](#overview)
- [Performance Review](#performance)
- [Footer](#footer)
- [Credits](#credits)

# Overview
[(Back to top)](#table-of-contents)

This repository contains a program for Image Classification using Augmentation. 

We are going to use 3 libraries for this project:
1. **os:** For Handling Directories using Python.
2. **random:** This library was used in the split function for establishing training and testing directories.
3. **tensorflow:** The main framework used for building the Convolutional Neural Network. Our main focus on this project is to explore the parameters of the ImageDataGenerator Function

For the Optimizer function, we are going to use the inbuilt tensorflow.keras.optimizers.RMSprop with a custom learning rate of 0.001.

The Dataset for this project was taken from the Kaggle Dogs vs. Cats Competition. Please participate in the competition for yourself and share your approach.

We will also make 4 directories using the os.makedir() function. The two main directories will be training and testing. Each of these directories have two folders named cats and dogs.

The model architecture is simple with 3 convolutional layers followed by Max Pooling. In the end there are 2 Dense Layers and a output layer with a single neuron with a sigmoid function. For compiling the model, we are using our optimizer with a custom learning rate and binary crossentropy as the loss function. 

The main focus of our project is the ImageDataGenerator Function. The following parameters were used:

- rotation range
- width shift range
- height shift range
- shear range
- zoom range
- horizontal flip
- fill mode


# Performance Review
[(Back to top)](#table-of-contents)

Accuracy Graph

![Alt Text](https://github.com/psych0man/Image-Classification-using-Augementation/blob/master/Performance%20Graphs.png)

Loss Graph

![Alt Text](https://github.com/psych0man/Image-Classification-using-Augementation/blob/master/Loss%20Graph.png)

# Footer
[(Back to top)](#table-of-contents)

Leave a star in GitHub, visit my blog and subscribe to it and share the code if you found this helpful.

# Credits
[(Back to top)](#table-of-contents)

This project was based upon the work of Laurence Moroney (@lmoroney) from the deeplearning.ai course on Coursera. You can find the original file [here](https://github.com/lmoroney/dlaicourse/blob/master/Course%202%20-%20Part%204%20-%20Lesson%204%20-%20Notebook.ipynb)

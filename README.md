# MachineLearingProject
The aim of the project is to apply what we have learnt in the class to a large real world dataset. 

The problem is to determine whether two images contain the face of the same celebrity. 
Instead of the raw images, you will work with a set of feature vectors that have been already been extracted from the images. 
Each training example is of the following form: 

Label   Features-of-Image-One Features-of-Image-Two

The Label is 1 if the same face is present in the images, and 0 otherwise. 
The features of each image is a 73 dimensional vector, thereby giving features in 146 dimensions. 
The features are various (noisy) attributes such as hair color, presence of sunglasses, etc, which are described in the file attributes.csv. 

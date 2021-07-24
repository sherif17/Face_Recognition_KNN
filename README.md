# Face_Recognition_KNN
We intend to perform face recognition. face recognition means that for a given image you can tell the subject id.

## Dataset & it's format Format :
* [ORL dataset is available at the following link](https://www.kaggle.com/kasikrit/att-database-of-faces)
* The dataset has 10 images per 40 subjects. Every image is a grayscale image of size 92x112.

## Generating the Data Matrix and the Label vector :

 * Converting every image into a vector of 10304 (92x112) values corresponding to the image Size.
 * Stack the 400 vectors into a single Data Matrix D and generate the label vector y.
 * The labels are integers from 1:40 corresponding to the subject id.

## Spliting the Dataset into Training and Test sets :

* From the Data Matrix D 400x10304 () we kept the odd rows for training and the even rows for testing.
* Spliting the labels vector accordingly.

## Classification using PCA 

## Classifier Tuning 

* Setting the number of neighbors in the K-NN classifier to 1,3,5,7.
* Plotting the performance measure (accuracy) against the K value.

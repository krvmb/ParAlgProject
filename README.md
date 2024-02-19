# ParAlgProject
Parallelizing Matrix Convolutions

In many areas of artificial intelligence, such as image detection, image classification, and natural language processing Convolutional Neural Networks(CNN) are extensively used.  These CNN’s primary mathematical operations are convolutions being applied to very large sets of data.  Computing these convolutions can be very expensive in terms of  processing time, and in CNN applications where decisions need to be made in real time, such as object detection in a camera feed, a faster method of matrix convolutions would be beneficial.
Matrix Convolutions are essentially a set of matrix multiplications where the input data is broken into different segments and multiplied by a kernel matrix.  By this description, it is evident that convolutions can be,and have been, parallelized.
The scope of this research project is to survey methods of parallelizing matrix convolutions, and seeing how this may improve the runtime of the sequential algorithm for matrix convolutions.

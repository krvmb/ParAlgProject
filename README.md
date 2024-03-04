# ParAlgProject
Parallelizing Matrix Convolutions

In many areas of artificial intelligence, such as image detection, image classification, and natural language processing Convolutional Neural Networks(CNN) are extensively used.  These CNN’s primary mathematical operations are convolutions being applied to very large sets of data.  Computing these convolutions can be very expensive in terms of  processing time, and in CNN applications where decisions need to be made in real time, such as object detection in a camera feed, a faster method of matrix convolutions would be beneficial.

Matrix Convolutions are essentially a set of matrix multiplications where the input data is broken into different segments and multiplied by a kernel matrix.  By this description, it is evident that convolutions can be,and have been, parallelized.

The scope of this research project is to survey methods of parallelizing matrix convolutions, and seeing how this may improve the runtime of the sequential algorithm for matrix convolutions.


REFERENCES

C. Yoo and S. Alawneh, "Accelerating 2-D Image Convolution Using a Graphics Processing Unit," 2021 IEEE Western New York Image and Signal Processing Workshop (WNYISPW), Rochester, NY, USA, 2021, pp. 1-5, doi: 10.1109/WNYISPW53194.2021.9661289. 

Jin, Peter H. et al. “Spatially Parallel Convolutions.” International Conference on Learning Representations (2018).

J. Lu, K. Zhang, M. Chen and K. Ma, "Implementation of parallel convolution based on MPI," Proceedings of 2013 3rd International Conference on Computer Science and Network Technology, Dalian, China, 2013, pp. 28-31, doi: 10.1109/ICCSNT.2013.6967057.

Pourghassemi, Behnam & Zhang, Chenghao & Lee, Joo & Chandramowlishwaran, Aparna. (2020). Brief Announcement: On the Limits of Parallelizing Convolutional Neural Networks on GPUs.

Vasudevan, Aravind et al. “Parallel Multi Channel convolution using General Matrix Multiplication.” 2017 IEEE 28th International Conference on Application-specific Systems, Architectures and Processors (ASAP) (2017): 19-24.

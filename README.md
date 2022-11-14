# Image-Quantization-using-K-Mean-Clustering

Colour quantization is a process that reduces the number of colours in an image while it tries to preserve the quality and the important global information. 
Images are composed of pixels each of which can be associated with 16,777,216 different colours in the case of RGB colour space, which is probably the most commonly used colour space. 
Each colour can be represented as a 3d vector, and each vector element has an 8-bit dynamic range, which means 2⁸=256 different values (i.e. 256x256x256 =16,777,216). 
This kind of representation is often called RGB triplet. 
The key factor for successful colour quantization is the appropriate selection of the colour palette that sufficiently summarizes the information of the initial image.
In this repository I used K-mean clustering to perform image quantisation.

# Super Resolution with SRCNN

SRCNN is a deep convolutional neural network that learns end-to-end mapping of low resolution to high resolution images.

The aim of the project is to deploy SRCNN using keras. Here is the original paper: [Image Super-Resolution Using Deep Convolutional Networks](https://arxiv.org/abs/1501.00092). The implementation is found in the notebook `srcnn.ipynb`

**Metrics used for evaluation:**
- Peak Signal to Noise Ratio (PSNR)
- Mean Squared Error
- Structural Similarity Index

**Data Used:**
I've used the same data as mentioned in the paper. You can download it from [here](http://mmlab.ie.cuhk.edu.hk/projects/SRCNN.html). Copy both the Set5 and Set14 datasets into a new folder called 'source'.

**Preparing data:**
- Produce low resolution version of the images through bilinear interpolation. 
- Save the new images in a folder.

The achitecture and hyper parameters necessary to build the SRCNN network can be obtained from the publication referenced above.

**Some Results:**
![](https://i.imgur.com/JyGqEsA.png)
![](https://i.imgur.com/RysE7jW.png)
![](https://i.imgur.com/WpRYToK.png)

**Future plans for this project:**
Compare all super resolution models including real-time video enhancement.
Currently working on implementing the new [SR3 paper](https://arxiv.org/abs/2104.07636). The results will be updated soon. 

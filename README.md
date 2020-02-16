## Project Overview

This project is done as a part of the Udacity's [Deep Learning Nanodegree](https://eu.udacity.com/course/deep-learning-nanodegree--nd101). The Generative Adversarial Network is trained over a preprocessed subset of [celeba dataset](https://drive.google.com/file/d/1PWYIxXk_yrGTozEpq7EOGkhzGl-T2bpT/view?usp=sharing). The trained model is then able to generate new faces.

GANs are implemented using PyTorch framework.

Fake generated faces by the project :
![faces](https://github.com/calincan2000/GenerateFaces/blob/master/assets/processed_face_data.png)


## Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/calincan2000/GenerateFaces.git
		cd GANs-Generate-Faces/
	```

2. Download the dataset zip file from [here](https://drive.google.com/file/d/1PWYIxXk_yrGTozEpq7EOGkhzGl-T2bpT/view?usp=sharing).
3. Open a terminal window and navigate to the project folder. Open the notebook using the bellow command and follow the instructions given in the notebook.
	
	```
		jupyter notebook dlnd_face_generation.ipynb
	```
	
### Getting Started

1. These notebook require PyTorch v0.4 or newer, and torchvision. The easiest way to install PyTorch and torchvision locally is by following the instructions on the PyTorch site which can be found on [link ](https://pytorch.org/get-started/locally/) . Choose the stable version, your appropriate OS and Python versions, and how you'd like to install it. You'll also need to install numpy and jupyter notebooks, the newest versions of these should work fine. Using the conda package manager is generally best for this,[conda install numpy jupyter notebook]

   If you haven't used conda before, [please read the documentation](https://conda.io/en/latest/) to learn how to create environments and install packages. I suggest installing Miniconda instead of the whole Anaconda distribution. The normal package manager pip also works well. If you have a preference, go with that.

   PyTorch uses a library called [CUDA](https://developer.nvidia.com/cuda-zone) to accelerate operations using the GPU. If you have a GPU that CUDA supports, you'll be able to install all the necessary libraries by installing PyTorch with conda. 

2. If you can't use a local GPU, you can use cloud platforms such as AWS, GCP, and FloydHub to train your networks on a GPU.[The project can be oppend also using  Google Colab](https://colab.research.google.com/) or using  [Kaggle Kernels](https://www.kaggle.com)
3. How to reproduce the results can be found in Jupyter Notebook  file the same dataset split between training and testing for predicting and checking the prediction

---

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
2. Install required dependencies using:
	
	```
		pip install -r requirements.txt
	```
3. Download the dataset zip file from [here](https://drive.google.com/file/d/1PWYIxXk_yrGTozEpq7EOGkhzGl-T2bpT/view?usp=sharing).
4. Open a terminal window and navigate to the project folder. Open the notebook using the bellow command and follow the instructions given in the notebook.
	
	```
		jupyter notebook dlnd_face_generation.ipynb
	```

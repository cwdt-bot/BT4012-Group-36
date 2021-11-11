BT4012 Group 36 
Authored by Darren Lee Sheng Hao A0201940U, Yap Kai Herng A0199729A

For your convenience, our 2 notebooks are also hosted on Google Colab:
Paper 1: https://colab.research.google.com/drive/13TauM-VGBMTr4JxOdLwKl9WqaPbtk8dx?usp=sharing
Paper 2: https://colab.research.google.com/drive/1xVjlCK3z1KtdCfNBHezJhvvrdwggC5B0?usp=sharing

###############################Pre-requisites######################################
Please take a look at paper_1_requirements.txt and paper_2_requirements.txt

You will need to have these packages installed on your system if you are running 
these notebooks locally.

Alternatively, if you are running them on Google Colab, you can ignore this pre-requisites section.

########### Paper 1: LightGBM for Online Click Fraud Detection.ipynb ##############
For this notebook to run properly, you will need to install LightGBM version 3.3.1 and above
This has been done for you in the first cell 

This notebook has been split into two sections, each corresponding a different dataset
Dataset 1: Click Fraud Detection (https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/data?select=train.csv)
Dataset 2: Credit Card Fraud Detection (https://www.kaggle.com/mlg-ulb/creditcardfraud )

For your convenience, these datasets have been hosted by us and can be easily downloaded using the !gdown cells

The structure of the notebook is as given 

-Dataset 1: Click Fraud
	- Importing Data
	- LightGBM on Click Fraud
		- Creation of LightGBM Dataset
		- LightGBM Training
		- LightGBM Feature Importance
	- XGBoost on Click Fraud
		- Data Preprocessing
		- XGBoost Training
		- XGBoost Feature Importance
	- Reducing Sample back to Original Ratio
		- Creation of LightGBM Dataset
		- LightGBM Training
		- LightGBM Feature Importance

-Dataset 2: Credit Card Fraud
	- LightGBM on Credit Card Fraud
		- Creation of LightGBM Dataset
		- LightGBM Training + Feature Importance
	- XGBoost on Credit Card Fraud
		- Data Preprocessing
		- Model Training
		- Feature Importance
		

########### Paper 2: Autoencoder + NeuralDF.ipynb ##############
For this notebook to run properly, you will need to downgrade Tensorflow to version 1.15
This has been done for you in the first cell

Dataset 1: https://github.com/dongmanqing/Opinion-Fraud-Detection-via-Neural-Autoencoder-Decision-Forest
Dataset 2: https://www.kaggle.com/vagifa/ethereum-frauddetection-dataset

A copy of the datasets are also hosted on our Google Drive accounts and can be downloaded
via the !gdown cells as provided.

Structure of the notebook is as follows:

- Downgrade tensorflow to V1

- Imports

- Loading Functions

- Download Datasets
	- Amazon Opinion Fraud (Used in Paper)
	- Ethereum Fraud

- Data Pre-processing
	- Amazon Opinion Fraud
	- Ethereum Fraud

- Model Parameters

- Model Functions
	- Utility Functions

- Actual Models
	- Autoencoder + Decision Forest
	- Autoencoder ReLUModification

- Fit Models
	- Amazon Opinion Fraud
		- Autoencoder + Neural DF
			- Original (sigmoid)
			- ReLU version
		- XGBoost
	- Ethereum Fraud
		- Autoencoder + Neural DF
			- Original (sigmoid)
			- ReLU version
		- XGBoost

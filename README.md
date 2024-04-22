# CheXpert Downsampled

## Environment
Our environment setup is running on a CUDA Graphics card with version 12.1 of the CUDA Toolkit on Windows.

We then created a new environment following the PyTorch "Start Locally" instructions, using the command line: 

`pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121`

We have also attached the YAML file to ensure that anyone who wishes to test the code can have an identical environment and package setup.

## Data and Notebook
* The notebook we are running uses only the training set of 500 samples and test set of 100 samples.
* We have marked down the remaining models for MURA's categories except for the Shoulder category, and we have marked down the VGG models for faster execution.

The complete dataset that we used can be found here:
* ConVirt Paper Image-image Retrieval and Text-image Retrieval Dataset (https://github.com/yuhaozhang/convirt)
* CheXpert Downsampled (https://www.kaggle.com/datasets/willarevalo/chexpert-v10-small)
* RSNA Pneumonia Detection (https://www.kaggle.com/competitions/rsna-pneumonia-detection-challenge/data)
* MURA (https://www.kaggle.com/datasets/cjinny/mura-v11/data)
* COVIDx CXR-4 (https://www.kaggle.com/datasets/andyczhao/covidx-cxr2)



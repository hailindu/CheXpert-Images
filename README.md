# Team-58

## Environment
Our environment setup is running on a CUDA Graphics card with version 12.1 of the CUDA Toolkit on Windows.

We then created a new environment following the PyTorch "Start Locally" instructions, using the command line: 

`pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121`

We have also attached the YAML file to ensure that anyone who wishes to test the code can have an identical environment and package setup.

## Data
The notebook we are running uses only the first 500 samples.

We are planning to transition to a cloud computing environment to process the entire dataset.

The complete dataset that we used can be found here:
[CheXpert-v1.0-small](https://www.kaggle.com/datasets/willarevalo/chexpert-v10-small)



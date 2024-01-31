# PyTorch Bootcamp

### This repository contains all my work throughout a [course](https://www.udemy.com/course/pytorch-for-deep-learning/?kw=pytorch&src=sac) on PyTorch offered by Daniel Bourke. 

You can find all the Jupyter notebooks that I have made along the way as well as the files I used to create 2 demo machine learning applications (FoodVision Mini and FoodVision Huge).

### FoodVision Mini
FoodVision Mini is a simple image classification application that classifies any image into 3 food categories: pizza, steak and sushi.\
The implementation can be found in [09_pytorch.ipynb](https://github.com/purplelord2003/PyTorch-Bootcamp/blob/main/Jupyter%20Notebooks/09_pytorch.ipynb).\
The application demo can be accessed via Hugging Face spaces [here](https://huggingface.co/spaces/purplelord2003/foodvision_mini).

### FoodVision Huge
FoodVision Huge is a ramped up version of FoodVision Mini which now classifies any image into [101 different food categories](https://github.com/purplelord2003/PyTorch-Bootcamp/raw/main/class_names.txt).
The implementation can be found in [09_pytorch.ipynb](https://github.com/purplelord2003/PyTorch-Bootcamp/blob/main/Jupyter%20Notebooks/09_pytorch.ipynb).\
The application demo can be accessed via Hugging Face spaces [here](https://huggingface.co/spaces/purplelord2003/foodvision_big).

### Summary
During the creation of the applications, there was a comparision between two model architecutures: [Efficient Net](https://arxiv.org/abs/1905.11946) (based on Convolutional Neural Networks) vs [Vision Transformer](https://arxiv.org/abs/2010.11929) (based on pure transformer). The decision to choose Efficient Net over Vision Transformer came down to considerations such as accuracy, model size and prediction speeds.

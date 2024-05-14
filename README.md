# Garbage Classification with PyTorch

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Welcome to the repository of our garbage classification project! We have developed a model using PyTorch and ResNet-18 that classifies garbage into six different types. The model has achieved an accuracy of **92.5%**.

## Dataset

The dataset used for this project is the [TrashType Image Dataset](https://www.kaggle.com/asdasdasasdas/garbage-classification) from Kaggle. It contains images of garbage, divided into six categories: metal, paper, glass, plastic, cardboard, and general trash.

## Model

We used the ResNet-18 model for this project. ResNet-18 is a convolutional neural network that is pretrained on the ImageNet dataset. It is known for its efficiency and high performance on a variety of image classification tasks.

## Installation

To run the code in this repository, you will need to install the required libraries. You can do this by running the following command:

```bash
pip install -r requirements.txt
```

## Usage

The main code for this project is in a Jupyter notebook named `Garbage_Classification.ipynb`. To run the notebook, use the following command:

```bash
jupyter notebook Garbage_Classification.ipynb
```

## Results

Our model achieved an accuracy of **92.5%** on the test set. This is a significant improvement over previous models, demonstrating the power of ResNet-18 and PyTorch.

## License

<pre>
 Copyright (c) 2024 Your Name
 
 This software is released under the MIT License.
 https://opensource.org/licenses/MIT
</pre>
```

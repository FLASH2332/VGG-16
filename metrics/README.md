# VGG-16 Flower Classification

This repository contains a VGG-16 based image classification workflow trained on the Oxford Flower dataset (segmented images variant used in this project).

## Dataset

- Source: https://www.kaggle.com/datasets/jd2005/oxford
- Download the dataset manually from Kaggle and extract it locally.

## Project Overview

- Model: VGG-16 transfer learning for flower classification
- Notebook: VGG-16-50.ipynb (50-epoch training run)
- Goal: classify flower images from segmented Oxford Flower data

## Kaggle Model

- Kaggle model page: https://www.kaggle.com/models/jd2005/vgg-16-1 , https://www.kaggle.com/models/jd2005/vgg-16-2
- Short model summary: Trained VGG-16 transfer learning model for Oxford Flower image classification using segmented input images.

## Setup

1. Clone this repository.
2. Create and activate a Python environment.
3. Install required packages (TensorFlow, NumPy, Matplotlib, scikit-learn, etc.).
4. Download and extract the dataset from Kaggle.
5. Update dataset paths in the notebook if needed.

## Expected Data Placement

Keep the extracted dataset outside git-tracked large archives. If placed inside this repository, add data paths to `.gitignore`.

Example structure:

```text
VGG-16/
	VGG-16-50.ipynb
	README.md
	dataset/
		...
```


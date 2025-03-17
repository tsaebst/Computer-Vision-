# Project: Animal Image Classification

This project focuses on classifying animal images using a Convolutional Neural Network (CNN). Deep learning methods are applied for image processing and analysis.

## Project Structure
- `Part_1_CV_Spitkovska.ipynb` – main notebook containing code for data analysis, dataset preparation, and model training.
- `README.md` – instructions on setting up the environment and running the project.
- `dataset/` – directory containing animal images.
- Additional notebooks and scripts will be added as the project evolves.

## ⚙️ Environment Setup
This project can be run in **Google Colab** or locally with Python.

###  Required Libraries
Ensure you have the following libraries installed:
```bash
pip install tensorflow torch torchvision matplotlib numpy opencv-python
import zipfile
import os
import torch
from torchvision import datasets, transforms
from collections import Counter
import matplotlib.pyplot as plt
import random
from torch.utils.data import DataLoader, random_split
```

### Setting up the Environment
#### Google Colab:
1. **Open Google Colab:** Navigate to [Google Colab](https://colab.research.google.com/).
2. **Create a new notebook:** Click on "File" → "New Notebook".
3. **Enable GPU:** Go to "Runtime" → "Change runtime type" and select "GPU".
4. **Upload the dataset or connect Google Drive:**
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
   Then, upload `Animals-10.zip` to Colab or access it from Google Drive using the [link](https://drive.google.com/file/d/1fRwkKSOHAlpzWrZmBMer6HM4vzKA7jdb/view?usp=drive_link)
   

#### Local Python Setup:
1. **Install Python:** Download and install Python from the [official site](https://www.python.org/).
2. **Install dependencies:** Run the following command in a terminal:
   ```bash
   pip install tensorflow torch torchvision matplotlib numpy opencv-python
   ```
3. **Download and extract the dataset:**
   - Unzip the `Animals-10.zip` file into a convenient directory.

## Running the Project
### In Google Colab:
- Upload the dataset or use Google Drive.
- Run the notebook.

### Locally:
- Ensure the dataset is extracted properly.
- Run Jupyter Notebook:
  ```bash
  jupyter notebook
  ```
- Open the appropriate `.ipynb` file and execute the cells.

## Author
**[Spitkovska Vladyslava]** – [https://github.com/tsaebst]


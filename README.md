# Animal-10 image cassificator

This project focuses on classifying animal images using a Convolutional Neural Network (CNN), either from scratch or pretrained. Among the methods applied were image preprocessing, augmentation, hyperparameter tuning, regularisation, model training, and work with pre-trained weights.

## Project Structure
- `CV_Project.ipynb` – main notebook containing code for data analysis, dataset preparation, model training, evaluation, and visualization.
- `README.md` – instructions on setting up the environment and running the project.
- `dataset/` – directory containing animal images.

## Environment Setup
This project can be run in **Google Colab** or locally with Python.
Recommended to use L4.

### Required Libraries
Ensure you have the following libraries installed:
```bash
pip install tensorflow torch torchvision  numpy opencv-python
!pip install tensorflow torch matplotlib
!pip install optuna
```
Other are listed in the notebook.

### Setting up the Environment
#### Google Colab:
1. **Open Google Colab:** Navigate to [Google Colab](https://colab.research.google.com/).
2. **Create a new notebook:** Click on "File" → "New Notebook".
3. **Enable CPU:** Go to "Runtime" → "Change runtime type" and select "CPU -> L4".
4. **Upload the dataset or connect Google Drive:**
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
   Then, upload `Animals-10.zip` to Colab or access it from Google Drive using the [link](https://drive.google.com/file/d/1fRwkKSOHAlpzWrZmBMer6HM4vzKA7jdb/view?usp=drive_link)
5. **Extract the dataset:**
   ```python
   #adjust path according to your directory with dataset
   with zipfile.ZipFile("/content/drive/MyDrive/Animals-10.zip", 'r') as zip_ref:
       zip_ref.extractall("/content/dataset")
   ```

#### Local Python Setup:
1. **Install Python:** Download and install Python from the [official site](https://www.python.org/).
2. **Install dependencies:** Run the following command in a terminal:
   ```bash
   pip install tensorflow torch torchvision  numpy opencv-python
   !pip install tensorflow torch matplotlib
   !pip install optuna   
   ```
3. **Download and extract the dataset:**
   - Unzip the `Animals-10.zip` file into a convenient directory.

## Running the Project
### In Google Colab:
- Upload the dataset or use Google Drive.
- Run the notebook `CV_Project.ipynb` step by step.

### Locally:
- Ensure the dataset is extracted properly.
- Run Jupyter Notebook:
  ```bash
  jupyter notebook
  ```
- Open `CV_Project.ipynb` and execute the cells.

## Author
**Spitkovska Vladyslava** – [GitHub](https://github.com/tsaebst)

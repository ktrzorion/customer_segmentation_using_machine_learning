# customer segmentation using machine learning
This repository contains the code for Customer Segmentation Using Agglomerative Clustering Algorithm and representation of result using Dendrograms.

For downloading dataset go to  : https://drive.google.com/file/d/1LleLWY-icTw5-qXbf9-Ynmj1F5UXk8MD/view?usp=share_link

NOTE: The code is in .ipynb format, for running the code without error in Google Colab edit in code


# Import libraries
from google.colab import drive
import pandas as pd

# Mount Drive with correct location of the file
drive.mount('/content/drive')

# Read CSV file using file path
data = pd.read_csv('/path/to/file.csv')

# Or, read CSV file using file name (if it's in the same directory)
data = pd.read_csv('file.csv')

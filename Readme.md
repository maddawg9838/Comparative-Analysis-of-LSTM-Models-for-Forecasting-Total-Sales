# Comparative Analysis of LSTM Models for Forecasting Sales

## Overview
This project creates LSTM Models from scratch (no libraries) and compares a Global LSTM (trained on all training data; all stores) versus Local LSTMs (trained on partitioned sets of the data; store type). Then produces a comparative metric table and visualizations for further analysis. 

## Files
- `LSTM Project.ipynb` - The Google Colab notebook containing the full analysis code

## Assumptions
- The Rossmann Store Sales dataset had a testing dataset without true labels, thus we utilized the training dataset and divided it into training, validating, and testing datasets.
- The hyperparameters are initialized in cell 38 (feel free to change all for personal testing EXCEPT INPUT_DIM)
  - INPUT_DIM = 1
  - HIDDEN_DIM = 4
  - LEARNING_RATE - 0.001
  - BATCH_SIZE = 32
  - EPOCHS = 3

## Instructions
1. Open [Google Colab](https://colab.research.google.com/).
2. Click **File → Upload notebook** and select `LSTM Project.ipynb`.
4. Make sure you are connected to the GPU runtime.
6. Run all cells sequentially (one at a time for best results). All necessary libraries are already imported and installed within the notebook.

## Notes
- No additional setup is required
- Data is fetched from a github public repository
- The uploaded Google Colab file includes the code and expected output

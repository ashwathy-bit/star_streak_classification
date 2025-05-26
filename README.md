# Star and Streak Classification from Astronomical Images

This project is part of an AI/ML internship assessment involving classification of astronomical objects in grayscale telescope images.

## Tasks:
- A1: Detect bright objects and extract centroid coordinates
- A2: Classify them as Star or Noise using a CNN
- A3: Report model accuracy and runtime

## Dataset
- 16-bit grayscale `.tiff` images (4418x4418)
- Extracted 128x128 patches for training

## Model
- CNN with 3 convolutional layers and a dense output
- Trained using manually labeled patches
- Accuracy on test set: 1.0

## How to Run
1. Open the notebook in Google Colab
2. Mount Google Drive and adjust the dataset path
3. Run the training or load the model from `my_model.keras`


## Notes
- Streak detection was skipped due to data limitations
- Manual labeling done using `ipywidgets`

## Author
Ashwathy Nair

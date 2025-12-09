# Face Mask Detection Project

## Overview
This project builds a Convolutional Neural Network (CNN) model to detect whether a person is wearing a face mask or not. It uses the MobileNetV2 architecture for high performance and efficiency.

## Requirements
- Python 3.x
- Libraries listed in `requirements.txt`

## Installation
1. Clone this repository or download the files.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
The project uses the [Face Mask Dataset](https://www.kaggle.com/omkargurav/face-mask-dataset) from Kaggle.
To download the dataset automatically via the notebook, you need to set up the Kaggle API:
1. Go to your Kaggle Account Settings and create a new API Token (`kaggle.json`).
2. Place the `kaggle.json` file in the root directory (where the notebook is) or in `~/.kaggle/`.
3. The notebook handles the download and extraction.

## Execution Procedure
1. Open the Jupyter Notebook `Face_Mask_Detection.ipynb`.
2. Run all the cells sequentially.
   - The notebook will download the dataset.
   - It will preprocess the images.
   - It will train the MobileNetV2 model.
   - It will evaluate the accuracy.
   - Finally, it shows a predictive system for testing on new images.

## Project Structure
- `Face_Mask_Detection.ipynb`: Main project code.
- `requirements.txt`: List of dependencies.
- `README.md`: Project documentation.
- `data/`: Directory where the dataset will be stored (created automatically).

# Breast Cancer Image Recognition App

## Project Overview

This project is an advanced image recognition application that utilizes breast ultrasound images for classifying cases into three categories: normal, benign, and malignant. The application leverages a trained machine learning model to assist in the early detection and classification of breast cancer, which is vital for reducing mortality rates.

### Dataset Details

- **Source:** Breast Ultrasound Dataset
- **Year Collected:** 2018
- **Participants:** 600 female patients aged between 25 and 75 years
- **Images:** 780 images with an average size of 500x500 pixels in PNG format
- **Classes:**
  - Normal
  - Benign
  - Malignant

The dataset includes both original and ground truth images, facilitating classification, detection, and segmentation tasks. Breast ultrasound images are highly effective when combined with machine learning techniques for medical diagnostics.

## Project Structure

```
breast-cancer-recognition-app
├── src
│   ├── app.py          # Main entry point of the application
│   ├── camera.py       # Manages camera operations
│   ├── model.py        # Loads the trained model and makes predictions
│   ├── utils.py        # Utility functions for image preprocessing
│   └── data
│       ├── benign      # Directory for benign images
│       ├── malignant   # Directory for malignant images
│       └── normal      # Directory for normal images
├── requirements.txt     # Project dependencies
├── README.md            # Project documentation
└── .gitignore           # Files and directories to ignore by Git
```

## Setup Instructions

1. Clone the repository:
   ```
   git clone https://github.com/atharv061166/breast-cancer-recognition.git
   cd breast-cancer-recognition
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Prepare your dataset:
   - Place images of benign cases in the `src/data/benign` directory.
   - Place images of malignant cases in the `src/data/malignant` directory.
   - Place images of normal cases in the `src/data/normal` directory.

## Usage Guidelines

1. Start the application:
   ```
   python src/app.py
   ```

2. Follow the on-screen instructions to upload images for classification.

3. The application will output the predicted class (normal, benign, or malignant).

## Model Information

The application employs a machine learning model trained on the Breast Ultrasound Dataset. Ensure that the model is properly trained and saved in the appropriate format before running the application. The training process leverages the unique characteristics of the dataset to achieve high accuracy in classification tasks.

## Contributions

Contributions to this project are welcome. Please feel free to fork the repository and submit pull requests with improvements or additional features.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.


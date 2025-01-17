# Emotion Recognition Model

This project demonstrates how to build and use an emotion recognition model using the FER2013 dataset. The model is created using `model_maker.py` and utilized in `main.py` to detect emotions based on input data.

---

## Project Structure

- **README.md**: This file provides an overview of the project.
- **main.py**: A script that uses the trained model to perform emotion recognition on input data.
- **model_maker.py**: A script for building and training the emotion recognition model using the FER2013 dataset.
- **test_labels.csv**: A file containing test labels for validating the model's performance.
- **requirements.txt**: A file listing all Python dependencies needed to run the project.

---

## Dataset

The model uses the FER2013 dataset, which is a publicly available dataset for facial expression recognition. You can download the dataset and provide its path when using `model_maker.py` to build the model.

---

## Installation

1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure the FER2013 dataset is downloaded and available.

---

## Usage

### Building the Model

1. Open the `model_maker.py` file and set the dataset path:
   ```python
   dataset_path = "path/to/fer2013"
   ```

2. Run the script to train and save the model:
   ```bash
   python model_maker.py
   ```

### Performing Emotion Recognition

1. Once the model is trained, use `main.py` to perform emotion recognition:
   ```bash
   python main.py
   ```

2. Provide the input (e.g., an image or test data) as required by the script. Refer to the `main.py` script for details.

---


## Notes

- Ensure the FER2013 dataset is preprocessed correctly for training.
- Modify the `model_maker.py` script if needed to customize model architecture or parameters.
- Validate the model's performance using the `test_labels.csv` file.

---

## License

This project is open-source and available under the MIT License.
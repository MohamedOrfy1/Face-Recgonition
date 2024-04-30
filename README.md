# Face-Recgonition
Face Detection and Recognition using Transfer Learning on Pins Face Recognition Dataset
# Celebrity Face Recognition with Cosine Similarity

This project implements a celebrity face recognition system using cosine similarity. Given an input image, the system identifies whether the image contains a celebrity from a predefined set of 105 classes. The system uses a pre-trained InceptionV3 model to extract features from the images and then calculates the cosine similarity between the input image and the dataset images to determine the closest match.

## Project Structure

The project is structured as follows:

- `preprocessed_dataset/`: Directory containing preprocessed images of celebrities.
- `weights/`: Directory containing pre-trained model weights.
- `README.md`: This README file.
- `face_recognition_cosine_similarity.ipynb`: Jupyter Notebook containing the project code.
- `face_recognition_cosine_similarity.py`: Python script containing the project code.
- `input_image.jpg`: Sample input image for testing.

## Usage

To use the project:

1. Ensure you have the required dependencies installed. You can install them using `pip install -r requirements.txt`.
2. Run the `face_recognition_cosine_similarity.ipynb` Jupyter Notebook or the `face_recognition_cosine_similarity.py` Python script.
3. Provide an input image to test the system. The system will output the predicted celebrity if the image contains a match from the dataset, otherwise, it will print "Unknown celebrity".

## Dependencies

The project relies on the following libraries:

- `numpy`
- `opencv-python`
- `scikit-learn`
- `tensorflow`
- `matplotlib`
- `plotly`
- `seaborn`
- `tqdm`

You can install them using `pip install -r requirements.txt`.

## Note

The dataset used in this project consists of preprocessed images of celebrities. The preprocessed dataset is available in the `preprocessed_dataset/` directory.

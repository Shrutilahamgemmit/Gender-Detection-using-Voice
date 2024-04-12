# Voice Gender Detection

This project is a gender detection system using machine learning (ML) techniques applied to voice data. The system includes a model trained on voice samples to predict the gender of speakers.

## Installation

To run this project, ensure you have the following dependencies installed:

- scikit-learn (`sklearn`)
- NumPy (`numpy`)
- pandas (`pandas`)
- joblib (`joblib`)
- librosa (`librosa`)

You can install these dependencies using pip:

```bash
pip install scikit-learn numpy pandas joblib librosa
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone <repository_url>
```

2. Navigate to the project directory:

```bash
cd voice-gender-detection
```

3. Open the Jupyter Notebook `voice.ipynb`:

```bash
jupyter notebook voice.ipynb
```

4. Run the cells in the notebook one by one.

5. In the last cell, provide the path of the testing voice file you want to check.

## File Structure

- `females/`: Directory containing voice samples labeled as females.
- `males/`: Directory containing voice samples labeled as males.
- `test/`: Directory for testing voice files.
- `voice_gender_detection_model.pkl`: Pre-trained ML model for gender detection.
- `voice.ipynb`: Jupyter Notebook containing the code for training and testing the model.
- `working.mov`: Working file.

## Testing

You can test the model by providing the path of a voice file located in the `test/` directory. The model will predict the gender of the speaker based on the provided voice sample.
css
Copy code
# Tacotron 2 Audio Preprocessor

This repository contains a Python script (`tacotron2_preprocessor.py`) that preprocesses audio files for training a Tacotron 2 text-to-speech model. The script trims silence, normalizes the audio, and saves the processed files to a specified output folder. It's specifically designed to work with .wav files to help create a clean and consistent dataset for Tacotron 2 model training.

## Requirements

- Python 3.6 or higher
- Librosa
- SoundFile

## Installation

1. Clone this repository to your local machine.

git clone https://github.com/yourusername/tacotron2-audio-preprocessor.git

markdown
Copy code

2. Install the required libraries:

pip install librosa soundfile

r
Copy code

## Usage

1. Update the `input_path` and `output_path` variables in the `tacotron2_preprocessor.py` script to point to your input folder containing the .wav files and the desired output folder for the processed files.

```python
input_path = "path\\to\\your\\input_folder"
output_path = "path\\to\\your\\output_folder"
Run the tacotron2_preprocessor.py script:
Copy code
python tacotron2_preprocessor.py

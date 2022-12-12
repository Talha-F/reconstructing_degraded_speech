# Project Overview

This project aims to reconstruct high-quality speech from degraded input. The code provided in this repository allows you to perform data augmentation on healthy speakers' speech and transcripts, and then use the augmented data to train a model for speech reconstruction.

# Dependencies
The following Python packages are required to run the code in this repository:
* datasets
* transformers==4.17.0
* jiwery
* jiwer
* librosa
* torchaudio_augmentations
* audio_augmentations

# Installation
To download and set up the code for this project, follow these steps:

Clone this repository to your local machine: git clone https://github.com/Talha-F/reconstructing_degraded_speech.git
1. Navigate to the project directory: cd speech-reconstruction
2. Install the required packages [refer to Dependencies section]
# Usage
To use the code in this repository to perform speech reconstruction, follow these steps:

1. Download the dataset from https://catalog.ldc.upenn.edu/LDC2012S02.
2. Since the speakers are grouped by gender (male and female), you will need to merge all speeches into a single directory (you may need to rename the files depending on how they are named). Do the same for the transcripts.
3. Load the healthy speakers data into the data augmentation file (either FC or MC).
4. After performing data augmentation, save the resulting data into the same directory as in step 2.
5. Load your data in the main file, Reconstructing_high_quality_speech_from_degraded_speech(ASR).ipynb.
6. Run the main file(Reconstructing_high_quality_speech_from_degraded_speech(ASR).ipynb) by opening it in Jupyter Notebook and running the cells.

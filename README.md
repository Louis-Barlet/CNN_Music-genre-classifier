# Deep Learning for Music Genre Classification
This project implements a convolutional neural network (**CNN**) to automatically classify audio files into musical genres. It is based on the concepts and code taught in **Valerio Velardo**'s ‘*Deep Learning for Audio*’ course (*The Sound of AI*).

## Description of the project
The project breaks down into two main parts:

1. *Extraction of audio features :*
   - Extraction of **MFCCs** (Mel-Frequency Cepstral Coefficients) from music files.
   - Saving the extracted data in **JSON** format for later use.
2. *Model construction, training and testing:*
   - Creation of a **CNN** model for classifying musical genres.
   - Training the model on a predefined dataset.
   - Adding predictions on external audio files that are not part of the initial dataset, in order to test the generalisation of the model.
   
## Pedagogical objective
This project enabled me to learn how to apply machine learning concepts to audio in practical terms. 
I have reproduced the concepts and code in a Jupyter Notebook so that I can run the code step by step and better understand each step. It allowed me also to easily add prediction steps to evaluate the model on other audio files. 

## Technologies used
- Python
- Librosa (for MFCC audio feature extraction)
- TensorFlow / Keras (for building and training the model)
- NumPy, Matplotlib (for data manipulation and visualisation)

## Credits
The project is based on the pedagogical content of **Valerio Velardo**'s ‘*Deep Learning for Audio*’ course (*The Sound of AI*).

# Speech Emotion Recognition

## Description

This project aims to recognize emotions in human speech using Machine Learning techniques. It uses various datasets such as RAVDESS, TESS, EMO-DB, and a custom dataset. The project is built with Python and uses libraries like TensorFlow, Librosa, NumPy, Pandas, SoundFile, Wave, Scikit-Learn, TQDM, Matplotlib, PyAudio, and FFMPEG.

## Datasets Used

This repository uses four datasets:

* **RAVDESS**: The Ryson Audio-Visual Database of Emotional Speech and Song.
* **TESS**: Toronto Emotional Speech Set.
* **EMO-DB**: A database of emotional utterances spoken by actors.
* **Custom**: An unbalanced noisy dataset that can be easily added to or removed from.

## Requirements

To run this project, you need to have the following Python packages installed:

* tensorflow
* librosa==0.6.3
* numpy
* pandas
* soundfile==0.9.0
* wave
* scikit-learn==0.24.2
* tqdm==4.28.1
* matplotlib==2.2.3
* pyaudio==0.2.11
* ffmpeg (optional)

You can install these packages using pip:


## Data Preprocessing

The core of this project lies in preprocessing audio files. We extract features from the audio files using LibROSA and store them in the storage using SoundFile.

## Models

We define a convolutional neural network (CNN) architecture with convolutional layers, pooling layers, and fully connected layers.
and train the CNN model using the extracted features and the corresponding emotion labels.

## Usage

To predict an emotion from an audio file, pass the audio path to the `rec.predict()` method:

## References

* [RAVDESS](http://www.emotionlab.com/dataset/ravdess/)
* [TESS](https://tspace.library.utoronto.ca/handle/1807/24487)
* [EMO-DB](https://emodb.bilderbar.info/home)

## License

This project is licensed under the terms of the MIT license.


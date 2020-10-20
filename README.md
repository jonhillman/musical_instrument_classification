# Musical Instrument Classification
In this notebook I explore musical instrument classification from audio using transfer learning leveraging [VGG-19](https://www.tensorflow.org/api_docs/python/tf/keras/applications/VGG19). The following is covered:
* Downloading samples from YouTube
* Reading sections of audio files into multiple sample arrays
* Generating mel-spectrograms for each sample
* Extracting 128-dimensional features from the mel-spectrograms using VGG-19
* Building test/train split from features array
* Classification with Linear Support Vector Machine (LinearSVM)

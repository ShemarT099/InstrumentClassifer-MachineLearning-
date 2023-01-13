# InstrumentClassifer-MachineLearning-


This project uses machine learning tools and algorithms to train the computer to recognize pre-labelled instruments based solely on their sounds.

Each instrument has it's own .wav file and there are 30 versions of 10 instruments

A MelSpectrogram from the librosa library was used to extract the features of each sound as each .wav file was iterated through. 

These features would then be assigned to a label to be prepared for a supervised learning model.

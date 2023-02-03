# InstrumentClassifer- MachineLearning- Audio Recognition


This project uses machine learning tools and algorithms to train the computer to recognize pre-labelled instruments based solely on their sounds.

Each instrument has it's own .wav file and there are 30 versions of 10 instruments

A MelSpectrogram from the librosa library was used to extract the features of each sound as each .wav file was iterated through. 

These features would then be assigned to a label to be prepared for a supervised learning model.

# Model

The Sequential model consisted of four layers; the input layer with a shape (40,), two hidden layers with 200 and 100 neurons respectively , and finally an output layer with 10 units representing the 10 different instruments

All layers had an activation function of 'ReLU' a linear function that returns the input as the output if it was positive, else the output returns 0. 
The ReLU activation function is usually easier to train and usually produces better performances 
# Applications

This is a program that demonstrates an algorithm's performance and accuracy at detecting muscial instruments with only playing a few seconds of music

# How to use?

To use this application, one can open this on a kaggle or jupyter notebook and then run each cell 

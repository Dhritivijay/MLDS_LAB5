Music Generation using RNN

This project implements a music generation system using a Recurrent Neural Network (RNN) built with TensorFlow and Keras.

The model is trained on MIDI files to learn musical patterns and sequences. It processes notes as sequential data and predicts the next note based on previously generated notes.

The architecture consists of an embedding layer for note representation, a SimpleRNN layer for capturing temporal dependencies, and a dense layer that outputs probability distributions over possible notes.

After training, the model generates new music by taking an initial seed sequence and predicting notes iteratively. A temperature parameter is used during sampling to control the randomness and creativity of the generated output.

The final generated sequence is converted back into MIDI format, allowing it to be played as a music file.

# privilaged_GAN_LSTM_music_generation
new learning framework for music generation

# description
This model is based on Privileged GAN v3 model architecture and we extract the musical information from the midi file using the music21 library. This library is used to extract a sequence of notes and chords present in the midi file. Then, we build the dictionary of notes to encode the notes into numbers and we find the sequence of numbers that represents the music considering the dictionary map. Then, build the model-based of privileged GAN v3 framework, each component of the model consists of an LSTM layer such that it works.





## output
An AI model that generates a sequence of music

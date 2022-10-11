# .WAV-File-Volume-Editor
A programme that modifies the volume of a .WAV file

Completed in part of Harvard's [CS50 - Introduction to Computer Science, 2020](https://cs50.harvard.edu/x/2020/).
This was Lab 4: [Volume](https://cs50.harvard.edu/college/2020/fall/labs/4/).

### Background
[WAV](https://docs.fileformat.com/audio/wav/) files are a common file format for representing audio. WAV files store audio as a sequence of “samples”: numbers that represent the value of some audio signal at a particular point in time. WAV files begin with a 44-byte “header” that contains information about the file itself, including the size of the file, the number of samples per second, and the size of each sample. After the header, the WAV file contains a sequence of samples, each a single 2-byte (16-bit) integer representing the audio signal at a particular point in time.

Scaling each sample value by a given factor has the effect of changing the volume of the audio. Multiplying each sample value by 2.0, for example, will have the effect of doubling the volume of the origin audio. Multiplying each sample by 0.5, meanwhile, will have the effect of cutting the volume in half.

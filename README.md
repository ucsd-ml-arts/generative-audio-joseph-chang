# Project 3 Generative Audio

Joseph Chang, jdchang@ucsd.edu

## Abstract

The goal of this project is to produce music and written text in Python using Machine Learning. This hands-off approach will allow artists to experiment with new music or find inspiration for new songs. A person will write whatever lyrics they want and DeepVoice will translate it into speech using a model created from a woman's voice. Performance RNN is then separately used to produce a music piece based on a combination of multiple, generated music phrases. These phrases are similar to a bass guitar audio clip on which the model was trained. Gansynth is used to interpolate a MIDI file of Frank Mill's Musicbox Dancer. Finally, the speech, generated music, and interpolated music are combined on the Davinci Resolve video editor. This project succeeds in producing comprehendable human speech and completely new music. However, it is not near the quality one would want from an actual artist. A future direction would be to include training a RNN model for singing rather than just speaking.

## Model/Data

Briefly describe the files that are included with your repository:
- trained models
- training data (or link to training data)

## Code

DeepVoice3 

https://colab.research.google.com/drive/1JpWuvyPCZqGdsXuclHqKidvf2yx_NFtc

Performance RNN & Gansynth 

https://colab.research.google.com/drive/1W6yGQP3bJ-IfvSpLgr9ELJ68jr6SBgES

## Results

https://www.youtube.com/watch?v=48HugqVAv9o

Documentation of your results in an appropriate format, both links to files and a brief description of their contents:
- `.wav` files or `.mp4`
- `.midi` files
- musical scores
- ... some other form

## Technical Notes

Any implementation details or notes we need to repeat your work. 
- Does this code require other pip packages, software, etc?
- Does it run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

Soundfonts4u - SGM-v2.01-Sal-Guit-Bass-V1.3.sf2 audio

https://sites.google.com/site/soundfonts4u/

Midiworld - Frank_Mills_-_Musicbox_Dancer.mid audio

https://www.midiworld.com/search/?q=dance

MIDI to MP3 Converter

https://www.online-convert.com/result/9cb76d5d-bee8-4ac5-be68-72409cc61c6e

MP3 Audio Joiner

https://audio-joiner.com/

MP3 to MIDI Converter

https://www.bearaudiotool.com/mp3-to-midi

Trim MIDI File

http://midi.mathewvp.com/midiTrim.php

References to any papers, techniques, repositories you used:
- Papers
- Repositories
- Blog posts

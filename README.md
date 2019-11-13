# Project 3 Generative Audio

Joseph Chang, jdchang@ucsd.edu

## Abstract

The goal of this project is to produce music and written text in Python using Machine Learning. This hands-off approach will allow artists to experiment with new music or find inspiration for new songs. A person will write whatever lyrics they want and DeepVoice will translate it into speech using a model created from a woman's voice. Performance RNN is then separately used to produce a music piece based on a combination of multiple, generated music phrases. These phrases are similar to a bass guitar audio clip on which the model was trained. Gansynth is used to interpolate a MIDI file of Frank Mill's Musicbox Dancer. Finally, the speech, generated music, and interpolated music are combined on the Davinci Resolve video editor. This project succeeds in producing comprehendable human speech and completely new music. However, it is not near the quality one would want from an actual artist. A future direction would be to include training a RNN model for singing rather than just speaking.

## Model/Data

DeepVoice is trained on the model 20180505_deepvoice3_ljspeech.json which is found online. The code automatically downloads it.

Performance RNN is run on the SGM-v2.01-Sal-Guit-Bass-V1.3.sf2 audio sample from Soundfonts4u which combines guitar and bass. 

- https://sites.google.com/site/soundfonts4u/

Gansynth interpolates on the Frank_Mills_-_ Musicbox_Dancer.mid audio from Midiworld.

- https://www.midiworld.com/search/?q=dance

## Code

DeepVoice3 

- https://colab.research.google.com/drive/1JpWuvyPCZqGdsXuclHqKidvf2yx_NFtc
- Description

Performance RNN & Gansynth 

- https://colab.research.google.com/drive/1W6yGQP3bJ-IfvSpLgr9ELJ68jr6SBgES
- Description

## Results

The resulting speech and music can be found in this repository. The text-to-speech generated by DeepVoice are the speech.wav files. The music generated by PerformanceRNN based on the guitar-bass audio are the music.mp3 files. The Musicbox Dancer music interpolated by Gansynth is the musicbox-gansynth.wav file.

The 8 speech outputs, 8 music outputs, and 1 interpolated song are combined in the DaVinci Resolve video editor and uploaded to YouTube for viewing.

https://www.youtube.com/watch?v=48HugqVAv9o


## Technical Notes

This implementation requires Google Colab which is an open source coding notebook. It only runs on Colab even though it is in Python Notebook format. 

## Reference

- [Online-Convert](https://www.online-convert.com/result/9cb76d5d-bee8-4ac5-be68-72409cc61c6e): MIDI to MP3 Converter
- [Audio-Joiner](https://audio-joiner.com/): MP3 Audio Joiner
- [Bear Audio](https://www.bearaudiotool.com/mp3-to-midi): MP3 to MIDI Converter
- Trim Midi File](http://midi.mathewvp.com/midiTrim.php): Trim MIDI File



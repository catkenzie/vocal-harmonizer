# Vocal Harmonizer
A real-time vocal harmonizer effects unit.  available as a VST plugin.
<!--This was a final project of a signals processing course.-->

## Getting Started

In order to see a small example of the project working, you can run initial\_prototype.m to hear harmonies from the "woods.mp3" file (which is located in the input_files) folder if you want to hear the input first.

### Modes of Operation

#### Mode 1
You can run "initial\_prototype.m" and change the FILENAME variable at the top to give any arbitrary input and hear the output.

#### Mode 2
If your computer has a microphone and you have headphones plugged in, you can run "realtime_testing.m" to hear the output of harmonies in real time!

#### Mode 3
If you have a DAW you can drag the vocalHarmonizer.vst file into your DAW's VST folder and use it immediately as an audio effect.

To regenerate the VST file, run the following commands
```
validateAudioPlugin vocalHarmonizer
generateAudioPlugin vocalHarmonizer
```


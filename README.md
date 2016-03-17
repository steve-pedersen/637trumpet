# 637trumpet About
Synthesizes a trumpet tone at 350Hz for 2.6 seconds. Trumpet tone created by additive synthesis using MPEG4-Structured Audio.
See included TrumpetEnvelopeDataTable PDF for the Harmonic table data used to generate trumpet tone.
Amplitude values are shorts (-32,768 to 32,768), so they are divided by 32,768 to get range -1 to 1.


# How to use:
1) Download and install Sfront 

  Source: https://john-lazzaro.github.io//sa/sfman/user/install/index.html#download 

2) Configure makefile:

  Change SFRONT variable in Makefile to wherever you unpacked Sfront

3) Compile and run:

  $ make

  $ open output.wav

4) To reset:

  $ make clean

5) To customize:

  Follow instructions in the SASL file about making chords. With the current SAOL code, sound files are limited to 2.6 seconds.
  To create more complex/longer arrangements, the SAOL file will need to be customized as well.
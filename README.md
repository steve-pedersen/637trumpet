# 637trumpet About
Synthesizes a trumpet tone at 350Hz.
Trumpet tone created by additive synthesis using MPEG4-Structured Audio.
See included TrumpetEnvelopeDataTable PDF for the Harmonic table data used to generate trumpet tone.
Amplitude values are shorts (-32,768 to 32,768), so they are divided by 32,768 to get range -1 to 1.

# How to use:
1) Download and install Sfront 
Source: https://john-lazzaro.github.io//sa/sfman/user/install/index.html#download 

2) Configure makefile:
Change SFRONT variable in Makefile to wherever you unpacked Sfront

3) Compile and run:
$ make
$ ./sa
$ open output.wav

4) To reset:
$ make clean
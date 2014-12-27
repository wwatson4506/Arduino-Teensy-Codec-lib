Arduino-Teensy-Codec-lib
======================

Audiolibrary plugin, plays up to 320 kbps MP3, MP4(AAC), M4A(AAC), AAC-Raw or FLAC in software without external hardware - 
with only 48MHz.

- Optimized for ARM Thumb2.
- Play from SD, built-in Flash or optional serial Flash (with audio-shield)
- Flac 4-24 BIT, Blocksize 128-1024 Bytes

planned:
 - streaming audio

 HINT: -O2 gives much better performance
 
 TODO:
 - detect APE-header
 - parse ID3 / APE / MP4 for extended information
 - ogg vorbis (?)
 
 not possible: SBR (aac-HE (low bitrate)) - (not enough ram).

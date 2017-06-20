# Solenoise
midi to embedded system compressed file format converter for windows

Solenoise was a project I made over the summer of 2016 that could robotically play a piano using an Arduino mega and an array of 60 solenoids.
Part of this project required a song to be stored on imbedded hardware, and to be playable by robot fingers. 

This program converts:

+ midi --> csv
+ csv  --> .h
+ .h   --> compressed .h

There is a batch script that performs all of these tasks and places each file that it creates in it's respective folder.

### Convert all on Windows

1. Place music file to convert in folder titled `midi/`
2. Run [`MIDItoCompH.bat`](https://github.com/spacerafe/Solenoise/blob/master/MIDItoCompH.bat)
3. When Prompted, enter name of file without .mid extension
4. File will be converted. Csv will reside in `csv/`. h file will be in `H/`. Compressed h file will be in `compressed_h/`.

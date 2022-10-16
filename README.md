# Split Audio File 
A simple script to split audio files based on cue files
reading supported formats : flac,wv,ape,alac
writing supported formats : flac,wav,ape,mp3

## Dependencies
cuetools shntool wavpack lame ffmpeg monkeys-audio libmac8
Monkeys audio & libmac8 debian installations packages are in this git 
all others can be installed using apt install <tool name>

## Unsupported
- this tool it is in beta mode , it does not support cue files with 1 single song (makes no sense splitting)
- this tool does not correct errors in cue files but it gives you a clew in how to fix the problem .
- does not support splitting flac, wv files encoded above 44Khz/16bit (shnsplit limitation)

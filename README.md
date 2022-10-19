# Split Audio File 
A simple script to split audio files based on cue files
reading supported formats : flac,wv,ape,alac
writing supported formats : flac,wav,ape,mp3

# Dependencies
cuetools shntool wavpack lame ffmpeg libc-bin monkeys-audio libmac8

- apt install cuetools shntool wavpack lame ffmpeg libc-bin monkeys-audio libmac8

If your linux does not have monkeys-audio & libmac8 then tool will install it
from tools folder in debian based system . It requires sudo or root to do it .

## Unsupported
- this tool it is in beta mode , it does not support cue files with 1 single song (makes no sense splitting)
- this tool does not correct errors in cue files but it gives you a clew in how to fix the problem .
- does not support splitting flac, wv files encoded above 44Khz/16bit (shnsplit limitation)

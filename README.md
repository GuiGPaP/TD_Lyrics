# TD_Lyrics
A Touchdesigner Component allowing user to process .lrc Lyric files

This TD script that takes a AudiofileIn, and a folder containing your lyrics : note the audio file and .lrc files must have the same name.

The TD script supports regular lyric files, but also enhanced lyrics file ( = multiple timecodes per sentence ).


It has a DAT and a TOP output for outputting lyrics, pretty basic ATM, but unlike usual lyrics decoder, this script is detecting lora embeddings, and allows a precise word control to 0.01s

Great to use with Dotsimulate StreamDiffusion component

# TD_Lyrics
A Touchdesigner Component allowing user to process .lrc Lyric files

This TD script that takes a AudiofileIn, and a folder containing your lyrics : note the audio file and .lrc files must have the same name.

The TD script supports regular lyric files, but also enhanced lyrics file ( = multiple timecodes per sentence ).


It has a DAT and a TOP output for outputting lyrics, pretty basic ATM, but unlike usual lyrics decoder, this script is detecting lora embeddings, and allows a precise word control to 0.01s

Great to use with Dotsimulate StreamDiffusion component


Also, here's a custom GPT allowing user to upload a .lrc file containing timecoded lyrics : 
This custom GPT will extract each sentence from lyric file, and transcribes them into a stable diffusion prompt.

In fact : the aim is to give a literal description in english of each word in a certain way that it can be understood by StableDiffusion/etc.

As the GPT is still experimental, i'm still modifying it in order to get a better prompt engineering. 
This would be nice to compare your original lyrics and modified ones, so I can have many good examples I can feed this GPT so it will produce better results. 

Link : https://chat.openai.com/g/g-vMzUw3xDd-sd-lyric-visualizer

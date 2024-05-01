# Andy Yang Assignment 8

1. Add a terminal screenshot of the server hosted on your machine.

See screenshot in folder

2. Add a streamlit UI screenshot with an audio transcription.

See screenshot in folder.

3. Notes: Everything worked as expected, except when deploying the model, I had to remove the "Z," from the -v flag. 

Additionally, I have trouble installing ffmpeg. I see that the command in the github repo 

"ffmpeg -i <input.mp3> -ar 16000 -ac 1 -c:a pcm_s16le <output.wav>"

requires a brew install of ffmpeg, not just a pip install. However, when I try to brew install it I get 

Error: You are using macOS 11.
We (and Apple) do not provide support for this old version.
It is expected behaviour that some formulae will fail to build in this old version.

One last thing, when I try to upload French_audio1.wav for example, I get a ValueError. The same thing happens when I use an online mp3 to wav converter, then upload that wav file. For some reason, the harvard wav file does not have this issue.

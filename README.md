# CasseteConverter
A thing so that I can plug an cassette tape player into my computer and then it splits tge tracks into individual audio files and saves them.

I got mixed results. 80% of the code is copy-pasted from stack-overflow. The ".idea" file is just for Pycharm, you can ignore that.

To use, you'll need a cassete tape player or something (I bet you could use a record player as long as it has an aux port) and a 3.5mm cable. Plug it into your computer as a microphone. Run the program and hit play on the player. Let it run until the player stops. It will save the recordings to your computer as low quality .wav files. When the player stops, terminate the program.

Experiment with threshold values for best results. For me, it worked best at 1000, but depending on your player/volume it might trigger false positives/not trigger anything at all (it just listens for silence)
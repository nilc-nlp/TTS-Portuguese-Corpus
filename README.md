# TTS-Portuguese-Corpus
To create the dadaset was used public domain texts.Initially, the texts were extracted from Wikipedia articles displayed in the Highlights section. In a second phase, texts were also extracted from  [Chatterbot-corpus](https://github.com/gunthercox/chatterbot-corpus/tree/master/chatterbot\_corpus/data/portuguese), a corpus originally created for the construction of chatbots. We also used 20 sets of phonetically balanced phrases, each set containing 10 phrases proposed by [Seara (1994)](https://repositorio.ufsc.br/bitstream/handle/123456789/112119/98594.pdf?sequence=1). The total number of words is 71,358, with 13,311 distinct words.

The base developed in this work has approximately 10 hours and 28 minutes of speech from a single speaker, recorded at 48Khz, containing a total of 3,632 audio files in Wave format. Audio files range from 0.67 to 50.08 seconds.

Since the audios were not recorded in an acoustic studio, there is noise present in the audio files, so we chose to use a noise suppression library. For this purpose we used the library [RNNoise](https://github.com/xiph/rnnoise) . It is based on Recurrent Neural Networks, more specifically Gated Recurrent Unit (GRU)  and demonstrated good performance for noise suppression. The base is open source, and public available under the terms of the license Creative Commons Attribution 4.0 (CC BY 4.0).


Cite:

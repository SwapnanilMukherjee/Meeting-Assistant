# Meeting Assistantext
 Parent repo containing all the modules for the Meeting Assistant Model
 
The algorithm for the Speech Transcription module is based on the paper by Google Brain named "Speaker Diarization with LSTM" (https://arxiv.org/abs/1710.10468) and the code is from the Resemblyzer library from this Medium article (https://medium.com/saarthi-ai/who-spoke-when-build-your-own-speaker-diarization-module-from-scratch-e7d725ee279). This is only the algorithm for getting the timestamps for different speakers. The code to convert the speech to text with appropriate speaker labelling will be added soon. Resemblyzer, Pydub, and spectralcluster must be installed on the machine for the code to run successfully. 

Link to sbert pretrained models for generation sentence embeddings:
https://www.sbert.net/docs/pretrained_models.html



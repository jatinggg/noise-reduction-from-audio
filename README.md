# noise-reduction-from-audio
Removing noise from audio using noisereduce library in python

This algorithm is based (but not completely reproducing) on the one outlined by Audacity for the noise reduction effect.
The algorithm requires two inputs:
  1. A noise audio clip comtaining prototypical noise of the audio clip
  2. A signal audio clip containing the signal and the noise intended to be removed

For more info visit https://pypi.org/project/noisereduce/ 

After removing voise pydub library is used to amplify the noise removed sample
For more info about pydub visit : http://pydub.com/

# Audio-Identification
An audio fingerprinting/matching algorithm based on that proposed by Wang (2003) (Shazam).

Fingerprinting is done by finding peaks in the spectrogram (See the fingerprint-builder notebook).

Matching is done through an optimized search algorithm that uses pairs of spectral peaks and their time difference as the hash keys.

Libraries/imports required:
- numpy
- librosa
- matplotlib
- skimage
- scipy

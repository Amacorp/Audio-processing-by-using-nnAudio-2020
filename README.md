# Audio-processing-by-using-nnAudio-2020

Audio processing by using pytorch 1D convolution network. By doing so, spectrograms can be generated from audio on-the-fly during neural network training. Kapre and torch-stft have a similar concept in which they also use 1D convolution from keras adn PyTorch to do the waveforms to spectrogram conversions.

Other GPU audio processing tools are torchaudio and tf.signal. But they are not using the neural network approach, and hence the Fourier basis can not be trained.

The name of nnAudio comes from torch.nn, since most of the codes are built from torch.nn.

Currently there are 3 models to generate various types of spectrograms

1. STFT
2. Mel Spectrogram
3. CQT




Source: https://github.com/KinWaiCheuk/nnAudio

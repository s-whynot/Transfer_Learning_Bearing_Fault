# Transfer_Learning_Bearing_Fault

3 class classification using the vibration data from the CWRU and the MFPT dataset. Created as part of my Master Thesis titled "Deep Learning Algorithms for Bearing Fault Classification".

Transfer Learning was implemented by having the CWRU dataset as the Source Domain and the MFPT dataset as the Transfer Domain. 2 files showing how it was gradually implemented. Originally it had the following strategy for transfer - CWRU to MFPT, MFPT to MFPT and CWRU to MFPT to MFPT. The second strategy is on a separate repository.

All codes were done in Python using Tensorflow library and the Keras API. A case of labeled Classification. These codes contain a Deep Neural Network (DNN) in the form of a Convolutional Neural Network (CNN). The base CNN structure was taken from https://www.hindawi.com/journals/sv/2017/5067651/

Basic code structure is done following the beautiful article https://blog.codecentric.de/en/2019/03/convolutional-neural-networks-damage-detection/

#cwru #mfpt #bearingfault #keras #tensorflow #deeplearning #cnn #transferlearning

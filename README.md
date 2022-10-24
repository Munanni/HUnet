# Deep learning-based framework for fast and accurate acoustic hologram

## Description
Our framework is for learned neural network which can rapidly generates accurate **acoustic hologram**.

The framework contains its architecture, networks, loss functions and datasets for training.
Autoencoder architecture with encoder(neural network) and decoder(simulation method, angular spectrum method).
Trains the encoder to make output of decoder indentical to the input of encoder.

![COMP_PIXELS_v2](https://user-images.githubusercontent.com/70740386/197447275-063e3a24-3184-4ae1-b83b-91707c9e9655.png)

![COMP_PIXELS_v2](https://user-images.githubusercontent.com/70740386/197447207-ec1ddfa7-1f4d-440c-9b11-b0f9ab3ae54c.png)

The paper addressed this framework is in revision now.


## Used environment
Python 3.8
Tensorflow 2.5
numpy 1.21.5
matplotlib
PIL
scipy
tqdm
skimage

## Usage
### Method
Select one of the methods in `main.py`.
1) Diff-PAT for phase-only holograms
2) Iterative angular spectrum approach (IASA)
3) Ours: HU-Net


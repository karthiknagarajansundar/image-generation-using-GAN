# image-generation-using-GAN

[//]: # (
[![Project Status: Unsupported – The project has reached a stable, usable state but the author(s) have ceased all work on it. A new maintainer may be desired.](https://www.repostatus.org/badges/latest/unsupported.svg)](https://www.repostatus.org/#unsupported) [![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
)

## Objective
The gist of the project is to implement a Variational Auto-Encoder (VAE), trained on MNIST data-set to generate images of digits between 0 and 9.

<img src="https://github.com/karthiknagarajansundar/image-generation-using-GAN/blob/main/images/vae.png" width="600" height="200">

## Experiments
#### Image generated using ADAptive Moment estimation (ADAM) architecture
<img src="https://github.com/karthiknagarajansundar/image-generation-using-GAN/blob/main/images/ImGenADAM.jpg" width="200" height="200">

#### Image generated using Stochastic Gradient Descent Momentum (SGDM) architecture
<img src="https://github.com/karthiknagarajansundar/image-generation-using-GAN/blob/main/images/ImGenSGDM.jpg" width="200" height="200">

#### Image generated with 1 hidden layer for encoder and 2 hidden layers for decoder
<img src="https://github.com/karthiknagarajansundar/image-generation-using-GAN/blob/main/images/1LEnc_2LDec.jpg" width="200" height="200">

#### Image generated with 2 hidden layer for encoder and 3 hidden layers for decoder
<img src="https://github.com/karthiknagarajansundar/image-generation-using-GAN/blob/main/images/2LEnc_3LDec.jpg" width="200" height="200">

## License
[MIT License](https://github.com/karthiknagarajansundar/image-generation-using-GAN/blob/main/LICENSE)

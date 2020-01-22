# Bollywood Faces  Variational Autoencoder

Variational Autoencoder for Bollywood actors face image generation implemented with PyTorch.

## Dataset
There is no publicly available Bollywood actors' face dataset, so I scrapped them from Google Image using Selenium. Faces from the images were extracted using dlib.


## Results

### Training
<div>
<img src='https://github.com/milsun/Bollywood-VAE/blob/master/images/loss.png', width="100%">
</div>

### Samples

Generated images are far from ideal, mainly because input data was quite dirty as I didn't have time to clean the data.



**Training images** (original vs. reconstruction)
<div>
	<img src='https://github.com/milsun/Bollywood-VAE/blob/master/images/valid_orig.png', width="48%">
  <img src='https://github.com/milsun/Bollywood-VAE/blob/master/images/valid_rec.png', width="48%">
</div>

**Testing images** (original vs. reconstruction)
<div>
	<img src='https://github.com/milsun/Bollywood-VAE/blob/master/images/sample_input_1.png', width="48%">
  <img src='https://github.com/milsun/Bollywood-VAE/blob/master/images/sample_output_1.png', width="48%">
</div>

<div>
<img src='https://github.com/milsun/Bollywood-VAE/blob/master/images/sample_input_2.png', width="48%">
  <img src='https://github.com/milsun/Bollywood-VAE/blob/master/images/sample_output_2.png', width="48%">
</div>

<br>
<br>

**New Samples**
<div>
	<img src='https://github.com/milsun/Bollywood-VAE/blob/master/images/gen.png', width="100%">
</div>
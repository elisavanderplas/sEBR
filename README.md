# sEBR
This script uses a Convolutional Neural Network to detect & compute the eye Blink Rate (sEBR) from face recordings

Spontaneous eye blink rate is an easily accessible proxy of striatal dopamine levels (for a review see Paprocki & Lenskiy, 2017, Frontiers in Human Neuroscience). There are various methods of calculating sEBR, whith the most common methods being (1) placing electrodes that on the Fp1 and Fp2 positions near the eye and counting the number of 'spikes' in signal amplitude, and (2) calculating the eye blinks 'manually' from a video recording. 

Given that the first method requires having expensive EEG equipment at one's disposition and that the second method is very prone to errors, I built upon this method from fchollet (https://gist.github.com/fchollet/0830affa1f7f19fd47b06d4cf89ed44d) to train a Convolutional Neural Network on detecting eye blinks from face recordings.  

See also the blog post "Building powerful image classification models using bery little data" from blog.keras.io

# Dependencies 

Jupyter Notebook

Keras

For plotting and stats: 

Numpy

Pandas

Matplotlib

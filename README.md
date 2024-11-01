# GTZAN genre classification example

This example is based on the excellent [Music Classification: Beyond Supervised Learning, Towards Real-world Applications](https://music-classification.github.io/tutorial/part3_supervised/tutorial.html) by Minz Won, Janne Spijkervet and Keunwoo Choi.

The code has a couple of structural changes compared to the version from the link above, but it does the same thing: music genre classification on GTZAN using a convnet.

GTZAN is a dataset that's considered the "MNIST of music AI". It's a genre classification dataset with 1000 tracks divided into 10 genres (multiclass classification). 
It's been very widely discussed in the music AI / music information retrieval community, but from an educational point of view it's a great dataset to get started with.

I higly recommend reading the the original GTZAN paper ["Musical Genre Classification of Audio Signals](https://www.cs.cmu.edu/~gtzan/work/pubs/tsap02gtzan.pdf) from 2002 by George Tzanetakis (G.Tzan, get it? 😉) and Perry Cook.

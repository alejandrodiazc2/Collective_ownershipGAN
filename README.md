# AI_4_Media_miniproject
 23036361_StyleGan2_tattoo_dataset

I've been doing art for about a decade, specifically tattoos. Therefore, I have collected a reasonable database (1,800 images), as I've documented them all. The data set consists of black & white images of designs selected by hundreds of different individuals tattooed on different parts of their bodies. In this project I use this as my base data for training from scratch a StyleGAN Model based on A Style-Based Generator Architecture for Generative Adversarial Networks article by Tero Karras, Samuli Laine, Timo Aila. I used TAUIL-Abd-Elilah StyleGAN from scratch in PyTorch implementation, due to environment and libraries compatibility issues with the original StyleGan repository that was linked in week 5 notebook. 

This adversarial network is then trained twice. The first time for 291 minutes for a 256 pixel size image and a second time for 1846 minutes for a 512 px output. This training was done with a NVIDIA 2080 GTX GPU. The output is two series of 100 images each, (256 and 512 pixels) which try to replicate the original dataset. This project questions the originality and ownership of artworks in the current AI world.  

The data set consists of around 1800 designs, some original designs and some variations of designs found on the internet. All of them tattooed by me on 1800 parts of human's flesh. I am aware that is a small number for training a model, but one of my main questions was the originality of the output, and it was very important the origin of the dataset. In this case, I know each of the elements of the data set, as I had to design them, trace them and then tattoo them. This information is then feed to a machine through the StyleGan architechture to create 100 unique images. It is also possible to see an animation on how the model creates the images from scratch.  

Who can claim ownership?  Are tattoo designs owned by the artist, or the person that has them permanently on their skins? Is an image downloaded from the internet but heavily manipulated still from the original author? Are  StyleGAN results owned by the authors of the paper that implemented it originally? We are facing hundreds of ethical and artistic questions in this fast evolving world, a world, in my opinion, of collective ownership.

Thanks for reading.

Github repo url: https://git.arts.ac.uk/alejandrozipa/AI_4_Media_miniproject.git
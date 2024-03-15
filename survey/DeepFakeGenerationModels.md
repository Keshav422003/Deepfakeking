# Generative Models in AI

1. VAE
2. UNET
3. GAN
4. Diffusion
5. AutoRegressive Flow based models

## Domains to check for

1. Sign Langauge
2. Fashion space.
3. Body motion generation
4. Pose transfere.
5. Face swap, generation.
6. Super resolution gans.
7. GAN Inversions

It to be checked that the latent space plays a major role. So any generative ai which deals with images can help us to give the embedding such as styleganv2. If the embeddings are rich enought that helps us to solve alot of work. These are necessary, since we are going to make a high res image in the end.

Ideally any architecture should be having 2 main components

1. Style Encoder
2. Content Encoder

The style encoder should be able to preserve the body shape, facial structure and skin tone.The content encoder shoule be able to encode the body keypose.The fusion module should be able to combine them and should be giving us the high precision generated output.A superres can help us to improve the resolution of the image.

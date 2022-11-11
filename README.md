# Stable diffusion
Stable Diffusion is based on a particular type of diffusion model called Latent Diffusion by Rombach et. at. 2021. General diffusion models are machine learning systems that are trained to denoise random gaussian noise step by step, to get to a sample of interest, such as an image. For a more detailed overview of how they work, check this colab.

Diffusion models have shown to achieve state-of-the-art results for generating image data. But one downside of diffusion models is that the reverse denoising process is slow. In addition, these models consume a lot of memory because they operate in pixel space, which becomes unreasonably expensive when generating high-resolution images. Therefore, it is challenging to train these models and also use them for inference.

## Componants 
The Latent diffusion consists of components:
1. An Auto - Encoder
2. A U-Net
3. A Text- Encoder

For details please read the paper by [Rombach et.al. 2021](https://arxiv.org/abs/2112.10752)

# XCube-Paper-Implementation

This repo contains my code implementing the architecture described in the following paper:

X3: Large-Scale 3D Generative Modeling using Sparse Voxel Hierarchies.

There are some notable differences between what is here and what is described in the paper. Firstly, this architecture only has 1 level. Secondly, this architecture is designed for voxel data of size 64^3 and is encoded into a latent space of 8^3. 

I have added some resources that I have found helpful during this work and references that I used. 

## Resources:
- XCube Paper: https://research.nvidia.com/labs/toronto-ai/xcube/
- VAE refresher: https://www.youtube.com/watch?v=H2XgdND0DV4
- Amazing explanation of the math of diffusion models: https://www.youtube.com/watch?v=HoKDTa5jHvg
- Part 1 of the following talk was very helpful in checking my understanding of the DDPMs: https://www.youtube.com/watch?v=cS6JQpEY9cs
- https://github.com/Stability-AI/stablediffusion/blob/main/ldm/modules/diffusionmodules/util.py
- V-Parameterization trick: https://arxiv.org/pdf/2202.00512.pdf
- Explanation of the straight through estimator: https://hassanaskary.medium.com/intuitive-explanation-of-straight-through-estimators-with-pytorch-implementation-71d99d25d9d0#:~:text=A%20straight%2Dthrough%20estimator%20is,function%20was%20an%20identity%20function.

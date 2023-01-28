# BrainMRI_Diffusion_Model
We are proposing a new model that applies denoising steps by UNet for improving the diffusion process to improve the result of medical image synthesis on Brain MRI scan Dataset.


Image synthesis is widely applied by GANs for
a few years, the result of GANs on medical images
are relatively satisfied but lack of flexibility and
the precision in image details [1]. The raising of
Diffusion models are showing the supreme outperformance
than GANs in Text-to-image generation
tasks, like DALL-E [2]. The images that generated
by Diffusion models are increasingly improving and
have a trending that is even better than human being’s
creations.[3] However, the original Diffusion
Models are suffering from slow reverse inference
time cost and the lack of stability of the result in
each Markov Chain. This is not ideal in medical
domain image generation. Hence, here we applied
a new Denoising Diffusion models that can be adjusted
and lower the noises in every few steps in the
reverse inference process. [4] are showing delightful
results by increasing step size T with this idea.
And hereby, we wish to use admitting a progressive
lossy decompression scheme that can be interpreted
as a generalization of autoregressive decoding [5] to
further improve the performance of [4]’s model.



References
1. H. Huang, P. S. Yu, και C. Wang, ‘An Introduction to Image 
Synthesis with Generative Adversarial Nets’. arXiv, 2018.
2. A. Ramesh κ.ά., ‘Zero-Shot Text-to-Image Generation’. arXiv, 2021.
3. J. Yu κ.ά., ‘Vector-quantized Image Modeling with Improved VQGAN’. arXiv, 2021.
4. M. Özbey κ.ά., ‘Unsupervised Medical Image Translation with Adversarial Diffusion Models’. arXiv, 2022.

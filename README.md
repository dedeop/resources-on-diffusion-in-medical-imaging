# Medical Image Outpainting
Compilation of papers covering both inpainting and outpainting in medical imaging

Outpainting:
| Title | Authors | Description |
| ----- | ------- | ----------- |
| [Body composition assessment with limited field-of-view computed tomography: A semantic image extension perspective](https://www.sciencedirect.com/science/article/abs/pii/S1361841523001123?via%3Dihub) | Kaiwen Xu, Thomas Li, Mirza S. Khan, Riqiang Gao, Sanja L. Antic, Yuankai Huo, Kim L. Sandler, Fabien Maldonado, Bennett A. Landman | Proposes a method in which a scan is artificially truncated so that the ground truth is known for training in order to expand the FOV of low dose CT scans |
|[Diffusion-based Generative Image Outpainting for Recovery of FOV-Truncated CT Images](https://arxiv.org/abs/2406.04769) | Michelle Espranita Liman, Daniel Rueckert, Florian J. Fintelmann, Philip Müller | Proposes a diffusion model which expands the FOV on truncated CT scans by generating noise around the masked area |
| [LOTUS: Latent Outpainting Diffusion Model for Three-Dimensional Ultrasound Stitching](https://openreview.net/forum?id=EyaeQLYCZP) | Xing Yao, Runxuan Yu, Nick DiSanto, Ehsan Khodapanah Aghdam, Kanyifeechukwu Jane Oguine, Daiwei Lu, Ange Lou, Jiacheng Wang, Dewei Hu, Gabriel A Arenas, Baris Oguz, Alison Marie Pouch, Nadav Schwartz, Brett Byram, Ipek Oguz | Proposes a diffusion model tested on expanding the FOV on Ultrasounds using a latent space to improve accuracy and efficiency |
| [Efficient Image-to-Image Schrodinger Bridge for CT Field of View Extension](https://arxiv.org/abs/2508.11211) | Zhenhao Li, Long Yang, Xiaojie Yin, Haijun Yu, Jiazhou Wang, Hongbin Han, Weigang Hu, Yixing Huang | Proposes a framework to extend the FOV of CT scans in a less computationally demanding way |
| [echoGAN: Extending the field of view in Transthoracic Echocardiography through conditional GAN-based outpainting](https://www.sciencedirect.com/science/article/pii/S016926072500286X) | Matej Gazda, Jakub Gazda, Samuel Kadoury, Robert Kanasz, Peter Drotar | Proposes a GAN model used to expand the FOV in cardiovascular ultrasounds | 

https://dl.acm.org/doi/10.5555/AAI28029340

https://www.sciencedirect.com/science/article/abs/pii/S0969806X21002851

https://openreview.net/pdf?id=4rFAhgrA0lA (might not apply)

Other Diffusion Models:
| Title | Authors | Description |
| ----- | ------- | ----------- |
| (might not apply) [Fast Controllable Diffusion Models for Undersampled MRI Reconstruction](https://ieeexplore.ieee.org/abstract/document/10635891 ) | Wei Jiang, Zhuang Xiong, Feng Liu, Nan Ye, Hongfu Sun | Proposes an approach for accelerating unsupervised diffusion models in the context of MRI reconstruction |

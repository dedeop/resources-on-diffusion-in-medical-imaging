# Medical Image Outpainting
The goal of this repository is to compile papers about outpainting in medical imaging with a focus on diffusion. Current research in this field is somewhat limited, so I've included some GAN research as well as inpainting. Thank you to all of the original authors for their work.

Outpainting:
| Title | Authors | Description |
| ----- | ------- | ----------- |
| [Body composition assessment with limited field-of-view computed tomography: A semantic image extension perspective](https://www.sciencedirect.com/science/article/abs/pii/S1361841523001123?via%3Dihub) | Kaiwen Xu, Thomas Li, Mirza S. Khan, Riqiang Gao, Sanja L. Antic, Yuankai Huo, Kim L. Sandler, Fabien Maldonado, Bennett A. Landman | Proposes a method in which a scan is artificially truncated so that the ground truth is known for training in order to expand the FOV of low dose CT scans |
|[Diffusion-based Generative Image Outpainting for Recovery of FOV-Truncated CT Images](https://arxiv.org/abs/2406.04769) | Michelle Espranita Liman, Daniel Rueckert, Florian J. Fintelmann, Philip Müller | Proposes a diffusion model which expands the FOV on truncated CT scans by generating noise around the masked area |
| [LOTUS: Latent Outpainting Diffusion Model for Three-Dimensional Ultrasound Stitching](https://openreview.net/forum?id=EyaeQLYCZP) | Xing Yao, Runxuan Yu, Nick DiSanto, Ehsan Khodapanah Aghdam, Kanyifeechukwu Jane Oguine, Daiwei Lu, Ange Lou, Jiacheng Wang, Dewei Hu, Gabriel A Arenas, Baris Oguz, Alison Marie Pouch, Nadav Schwartz, Brett Byram, Ipek Oguz | Proposes a diffusion model tested on expanding the FOV on Ultrasounds using a latent space to improve accuracy and efficiency |
| [Efficient Image-to-Image Schrodinger Bridge for CT Field of View Extension](https://arxiv.org/abs/2508.11211) | Zhenhao Li, Long Yang, Xiaojie Yin, Haijun Yu, Jiazhou Wang, Hongbin Han, Weigang Hu, Yixing Huang | Proposes a framework to extend the FOV of CT scans in a less computationally demanding way |
| [echoGAN: Extending the field of view in Transthoracic Echocardiography through conditional GAN-based outpainting](https://www.sciencedirect.com/science/article/pii/S016926072500286X) | Matej Gazda, Jakub Gazda, Samuel Kadoury, Robert Kanasz, Peter Drotar | Proposes a GAN model used to expand the FOV in cardiovascular ultrasounds | 
| [Generation of tissues outside the field of view (FOV) of radiation therapy simulation imaging based on machine learning and patient body outline (PBO)](https://ro-journal.biomedcentral.com/articles/10.1186/s13014-023-02384-4) | Sunmi Kim, Lulin Yuan, Siyong Kim, Tae Suk Suh | desc |


Inpainting: 
| Title | Authors | Description |
| ----- | ------- | ----------- |
| (https://ieeexplore.ieee.org/abstract/document/8682677) |  | desc |
| (https://ieeexplore.ieee.org/abstract/document/9191207) |  | desc |
| (https://arxiv.org/abs/2506.23038) |  | desc |
| (https://arxiv.org/abs/2411.10686) |  | desc |
| (https://arxiv.org/abs/2406.02477) |  | desc |

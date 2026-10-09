# Research in 3D Vision

I am an undergraduate in Surveying and Mapping Engineering at Jilin University. My projects focus on reproducing, adapting, and evaluating open-source research code for visual reconstruction and perception.

**Research Interests:** 3D Vision, 3D Reconstruction, SLAM, Spatial Intelligence, Robot Perception.

## Selected Projects

- **[Gaussian Splatting Reconstruction](https://github.com/whywherewho/gsplat-multiview-reconstruction)** — Adapted Nerfstudio's Splatfacto pipeline on ETH3D kicker, from COLMAP preprocessing to GPU optimization and held-out rendering. Compared 12 and 24 training views using PSNR, SSIM, and LPIPS under a shared SfM solution.
- **[Transformer-based Metric Depth Fine-tuning](https://github.com/whywherewho/metric-depth-finetuning)** — Fine-tuned the official Depth Anything V2 Small metric checkpoint on a small NYU RGB-D subset. Implemented a PyTorch training and validation workflow and compared head-only with partial-backbone fine-tuning.

These are small experimental projects built on upstream methods and pretrained models. Each repository includes the project code, measured results, reproduction instructions, and evaluation limitations.

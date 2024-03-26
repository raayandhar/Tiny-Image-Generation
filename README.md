# Tiny-Image-Generation

ECE C147 (Neural Networks & Deep Learning) final project. Implemented DDIM, DDPM, and PixelCNN generative models. See report for details.

## Abstract
This paper presents a study of small image size generative modeling using diffusion models and PixelCNN. Our experiments are focused on two `tiny image' datasets, optimized for our computational constraints. By analyzing the interpolation in our diffusion models, investigating various beta and noise schedules, and evaluating the denoising capabilities at different sampling steps, we provide novel insights into the mechanisms and effectiveness of each model type.

We measure the quality of generated images using FID scores and validate model performance through qualitative and quantitative assessments. The outcomes of this study illuminate the strengths and limitations of each approach, with particular attention to the adaptation of diffusion models for small image sizes. The results have promising implications for the application of these models in domains where computational efficiency is paramount.

### Score:
(across both graders)
Creativity: 7/7
Insight: 7/7
Performance: 6/6
Write-up: 4/4

To run, 
1. `git clone https://github.com/raayandhar/Tiny-Image-Generation.git`
2. Run the following:
```bash
conda create Diffusion_IIG python=3.11.5 ipython
conda activate Diffusion_IIG
pip install -r requirements.txt
```


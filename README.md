## <div align="center"> GenDR⚡: Lightning Generative Detail Restorator </div>

<div align="center"> 

[Yan Wang](https://scholar.google.com/citations?user=SXIehvoAAAAJ&hl=en), Shijie Zhao<sup>†</sup>, Kai Chen, Kexin Zhang, [Junlin Li](https://scholar.google.com/citations?user=daHqpg8AAAAJ&hl=en&oi=ao), [Li Zhang](https://scholar.google.com/citations?hl=en&user=8G5-2OMAAAAJ) 
</div>

<p align="center"> ByteDance
  
<p align="center">
<a href="https://icandle.github.io/gendr_page/">
    <img src="https://img.shields.io/badge/Project-GenDR-FF8C00" /></a>
<a href="https://arxiv.org/abs/2503.06790" alt="arXiv">
    <img src="https://img.shields.io/badge/arXiv-2503.06790-b31b1b.svg?style=flat" /></a>
<a href="https://drive.google.com/file/d/18FW1SuoayABoes8l9ntKuk-xWi5b89Ye/view?usp=sharing">
    <img src="https://img.shields.io/badge/Docs-NoComp&Sup-8A2BE2" /></a>

---

<p align="center">
<img src="./figures/polar.png" width=55% height=50% class="center">
</p align="center">

**Overview:** This work presents a ***one-step*** diffusion model for generative detail restoration, **GenDR**⚡, distilled from a tailored diffusion model with ***larger latent space***, to eliminate the dilemma arised by misalignment between T2I and SR tasks. 1) ***SD2.1-VAE16***: To expand a high-dimensional latent space without enlarging model size, we train a new SD2.1-VAE16 (0.9B) via representation alignment. 2) ***CiD/CiDA***: We propose consistent score identity distillation (CiD) incorporating SR task-specific loss into score distillation to leverage more SR priors and align the training target. Furthermore, we extend CiD with adversarial learning and representation alignment (CiDA) to enhance perceptual quality and accelerate training.  

[<img src="./figures/sli4.png" width=100% height=100% 
class="left">](https://imgsli.com/MzU4NDEx)


<details>
<summary>More visual comparison from RealDeg (click me)</summary>
<p align="left">

#### Social Media
  
[<img src="./figures/sli1.png" width=49% height=49% 
class="left">](https://imgsli.com/MzU4Mzk4)
[<img src="./figures/sli2.png" width=49% height=49% 
class="left">](https://imgsli.com/MzU4NDAy)
[<img src="./figures/sli3.png" width=49% height=49% 
class="left">](https://imgsli.com/MzU4NDA4)
[<img src="./figures/sli3b.png" width=49% height=49% 
class="left">](https://imgsli.com/MzU4NDMz)


#### Classic Film

[<img src="./figures/sli5.png" width=49.6% height=51% 
class="left">](https://imgsli.com/MzU4NDE2)
[<img src="./figures/sli6.png" width=49% height=49% 
class="left">](https://imgsli.com/MzU4NDE4)
[<img src="./figures/sli7.png" width=56% height=49% 
class="left">](https://imgsli.com/MzU4NDMx)
[<img src="./figures/sli7c.png" width=42% height=49% 
class="left">](https://imgsli.com/MzU4NDM2)

#### Old Photo

[<img src="./figures/sli8.png" width=48% height=49% 
class="left">](https://imgsli.com/MzU4NDMw)
[<img src="./figures/sli9.png" width=50.5% height=49% 
class="left">](https://imgsli.com/MzU4NDM4)
[<img src="./figures/sli11.png" width=60% height=49% 
class="left">](https://imgsli.com/MzU4NDQz)
[<img src="./figures/sli10.png" width=38% height=49% 
class="left">](https://imgsli.com/MzU4NDQx)
[^_^]: # [<img src="./figures/sli12.png" width=49% height=49% class="left">](https://imgsli.com/MzU4NDQ2)

</p>
</details>


<details>
<summary>More visual comparison from RealLR200 (click me)</summary>
<p align="left">

</p>
</details>

The repo is still under construction.

🔥 Update
---
- [2025.03] Repo and project created. The open-source process is in the audit stage and depends on the company policy. If all goes well, the code and weights will be released in the next two months.

💖 Acknowledgments
---
We would thank [Ostris](https://huggingface.co/ostris/vae-kl-f8-d16), [RealESRGAN](https://github.com/xinntao/Real-ESRGAN/tree/master/realesrgan), [OSEDiff](https://github.com/cswry/OSEDiff/blob/main/osediff.py), [SiD](https://github.com/mingyuanzhou/SiD), etal for their enlightening work!

🎓 Citation
---
```
@article{wang2025gendr,
  title={GenDR: Lightning Generative Detail Restorator},
  author={Wang, Yan and Zhao, Shijie and Chen, Kai and Zhang, Kexin and Li, Junlin and Zhang, Li},
  journal={arXiv preprint arXiv:2503.06790},
  year={2025}
```

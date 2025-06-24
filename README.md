# Imagic: Text-Based Real Image Editing with Diffusion Models [CVPR 2022]

<a href="https://imagic-editing.github.io/"><img src="https://img.shields.io/static/v1?label=Project&message=Website&color=blue"></a> 
<a href="https://arxiv.org/pdf/2210.09276"><img src="https://img.shields.io/badge/arXiv-2210.09276-b31b1b.svg"></a>
[![Related Project](https://img.shields.io/badge/GitHub-Reference--Repo-green?logo=github)](https://github.com/justinpinkney/stable-diffusion)

---

![Figure 1](image/fig1)

---

# 📌 Notice

This repository is a customized implementation of **Imagic**, a diffusion-based real image editing method guided by text prompts.  
Built upon [justinpinkney/stable-diffusion](https://github.com/justinpinkney/stable-diffusion), with added support for fine-tuning and editing specific real-world images.

---

# 🛠️ Getting Started

## 🧩 Installation

### 1. Create and activate virtual environment

```bash
conda create --name imagic python=3.10 -y
conda activate imagic

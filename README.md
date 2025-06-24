# Imagic: Text-Based Real Image Editing with Diffusion Models [CVPR 2022]

<a href="https://imagic-editing.github.io/"><img src="https://img.shields.io/static/v1?label=Project&message=Website&color=blue"></a> 
<a href="https://arxiv.org/pdf/2210.09276"><img src="https://img.shields.io/badge/arXiv-2210.09276-b31b1b.svg"></a>
[![Related Project](https://img.shields.io/badge/GitHub-Reference--Repo-green?logo=github)](https://github.com/justinpinkney/stable-diffusion)

---

![Figure 1](images/fig1)

---

# 📌 Notice
> This repository is based on [justinpinkney/stable-diffusion](https://github.com/justinpinkney/stable-diffusion) and adapted for implementing the **Imagic** framework (CVPR 2022).

---

# 🛠️ Getting Started

## 🧩 Installation
### 1. 참고한 github 복제 및 이동
```bash
git clone https://github.com/justinpinkney/stable-diffusion.git
cd stable-diffusion
```

### 2. 가상환경 만들기

```bash
conda create --name imagic python=3.10 -y
conda activate imagic
```

### 3. 라이브러리 설치
```bash
pip install torch==2.2.2 torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
pip install -r requirement.txt
pip install -e git+https://github.com/CompVis/taming-transformers.git@master#egg=taming-transformers
pip install -e git+https://github.com/openai/CLIP.git@main#egg=clip
```
## 🔨 Imagic 사용하기
`notebooks/imagic.ipynb` 파일을 실행하여 Imagic을 사용

### Module Import Error
코드 실행 중 `clip`, `taming` 모듈을 찾을 수 없다는 오류가 발생할 때:
1. 설치된 모듈 위치 확:
```bash
!pip show clip 
```
2. 경로 수동 추가:
```
import sys
sys.path.append('Location path/clip') #경로 추가

import clip
```


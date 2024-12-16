<div align=center>

# Predicting the Original Appearance of Damaged Historical Documents

</div>

![HDR_LOGO](figures/logo.png)  

<div align=center>

[![arXiv preprint](http://img.shields.io/badge/arXiv-2312.12142-b31b1b)](https://arxiv.org/abs/2312.12142) 
[![Homepage](https://img.shields.io/badge/Homepage-HDR-green)](https://yeungchenwa.github.io/fontdiffuser-homepage/)
[![Code](https://img.shields.io/badge/Code-HDR-yellow)](https://github.com/yeungchenwa/HDR)

</div>

<p align="center">
   <strong><a href="#🖼️-Gallery">🖼️ Gallery </a></strong> •
   <strong><a href="#📊-HDR28K">📊 HDR28K </a></strong> •
   <strong><a href="#🔥-Model-Zoo">🔥 Model Zoo</a></strong> •
   <strong><a href="#🚧-Installation">🚧 Installation</a></strong> •
   <strong><a href="#📺-Inference">📺 Inference</a></strong> •
   <strong><a href="#📏-Evaluation">📏 Evaluation</a></strong>
</p>

## 🌟 Highlight
![Vis_1](figures/highlight_0.png)
![Vis_2](figures/highlight_1.png)
+ We introduce a <u>H</u>istorical <u>D</u>ocument <u>R</u>epair **(HDR)** task,
which endeavors to predict the original appearance of
damaged historical document images.
+ We build a large-scale historical document repair dataset,
termed **HDR28K**, which includes <u>28,552</u> damaged-repaired image pairs with **character-level annotations** and **multi-style degradation**.
+ 🔥🔥🔥 We propose a <u>Diff</u>usion-based <u>H</u>istorical <u>D</u>ocument <u>R</u>epair method **(DiffHDR)**, which augments the DDPM framework with semantic and spatial information

## 📰 News
- **2024.12.17**: Release inference code.   
- **2024.12.10**: 🎉🎉 Our [paper]() is accepted by AAAI2025.   

## 🏗️ TODO List
- [x] Inference Code.
- [ ] HDR28K Dataset Release.
- [ ] Repair Demo.
- [ ] Traning Code. (Maybe release, due to the copyright)

## 🔥 Model Zoo
| **Model**                                    | **chekcpoint** | **status** |
|----------------------------------------------|----------------|------------|
| **DiffHDR**                              | [GoogleDrive](https://drive.google.com/drive/folders/1ArP21T7vyTpbPb5qC5VV76pMUsQd4tCx?usp=sharing) / [BaiduYun:x62f](https://pan.baidu.com/s/1XpoGvQHruOQjzJDEymsXzg) | Released  |

## 🚧 Installation
### Prerequisites (Recommended)
- Linux
- Python 3.9
- Pytorch 1.13.1
- CUDA 11.7

### Environment Setup
Clone this repo:
```bash
git clone https://github.com/yeungchenwa/HDR.git
```

**Step 0**: Download and install Miniconda from the [official website](https://docs.conda.io/en/latest/miniconda.html).

**Step 1**: Create a conda environment and activate it.
```bash
conda create -n diffhdr python=3.9 -y
conda activate diffhdr
```

**Step 2**: Install related version Pytorch following [here](https://pytorch.org/get-started/previous-versions/).
```bash
# Suggested
pip install torch==1.13.1+cu117 torchvision==0.14.1+cu117 torchaudio==0.13.1 --extra-index-url https://download.pytorch.org/whl/cu117
```

**Step 3**: Install the required packages.
```bash
pip install -r requirements.txt
```

## 📺 Inference

## 📊 HDR28K
```bash
Coming soon ...
```

## 📏 Evaluation
```bash
Coming soon ...
```

## 🖼️ Gallery

## 💙 Acknowledgement

## ⛔️ Copyright

## 📇 Citation

## 🌟 Star Rising

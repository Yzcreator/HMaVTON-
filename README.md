# Smart Fitting Room: A One-stop Framework for Matching-aware Virtual Try-On
This is the implementation of our paper at ICMR 2024:
> [Smart Fitting Room: A One-stop Framework for Matching-aware Virtual Try-On](https://arxiv.org/abs/2401.16825)
> 
> Mingzhe Yu, Yunshan Ma, Lei Wu*, Kai Cheng, Xue Li, Lei Meng, Tat-Seng Chua

![Model for this project](figures/model.png)

## TODO List
- [x] Environment
- [ ] Shape Constraint Network
- [ ] Matching Clothes Diffusion Network
- [ ] Try-on Condition Generator
- [ ] Denoising Generator
- [ ] Datasets
- [ ] Release checkpoint

## Installation
Clone this repository:
```
git clone https://github.com/Yzcreator/HMaVTON.git
cd ./HMaVTON/
```
Install PyTorch and other dependencies:
```
conda env create -f environment.yaml
conda activate control
```





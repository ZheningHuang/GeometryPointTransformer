# Geometry Point Transformer

This repository contains the code for our paper "Geometry Point Transformer for Point Cloud Segmentation.


<p align="center">
  <img src="Geometry PT.png" width="480">
</p>

# News
Code and pre-train model will be released on Feb 2022

# Overview

This codebase includes the following:

- A full implementation of the Geometry Point Transformer
- Pre-trained models for achieving state-of-the-art results on various datasets

## Requirments:

- Ubuntu: 18.04 or higher
- CUDA: 10.2 or higher
- PyTorch: 1.10.0 ~ 1.11.0
- Hardware: GPUs with memory > 24G


<!-- 
## Installation for main architecture:

```bash
conda create -n GeometryPT python=3.8 -y
conda activate GeometryPT
conda install ninja -y
conda install pytorch==1.10.1 torchvision==0.11.2 torchaudio==0.10.1 cudatoolkit=11.3 -c pytorch -c conda-forge -y
conda install -c anaconda h5py pyyaml -y
conda install -c conda-forge sharedarray tensorboardx yapf addict einops scipy plyfile termcolor timm -y
conda install -c pyg pytorch-cluster pytorch-scatter pytorch-sparse -y
pip install torch-geometric
```

## Installation for geometry partition module:


**Step 1:** Install Boost (1.63.0 or newer) and Eigen3 in conda:

```
conda install -c anaconda boost
conda install -c omnia eigen3
conda install eigen
conda install -c r libiconv
```

**Step 2:** Compile the ```libply_c``` and ```libcp``` libraries

```
CONDAENV=YOUR_CONDA_ENVIRONMENT_LOCATION 
cd partition/ply_c
cmake . -DPYTHON_LIBRARY=$CONDAENV/lib/libpython3.8.so -DPYTHON_INCLUDE_DIR=$CONDAENV/include/python3.8 -DBOOST_INCLUDEDIR=$CONDAENV/include -DEIGEN3_INCLUDE_DIR=$CONDAENV/include/eigen3
make
cd ..
cd cut-pursuit
mkdir build
cd build
cmake .. -DPYTHON_LIBRARY=$CONDAENV/lib/libpython3.8.so -DPYTHON_INCLUDE_DIR=$CONDAENV/include/python3.8 -DBOOST_INCLUDEDIR=$CONDAENV/include -DEIGEN3_INCLUDE_DIR=$CONDAENV/include/eigen3
make
```

## Data Preparation
### *Geometry Partition Modules*


## Quick Start for Geometry Point Transformer


## Model

## Citation

## Acknowledgement -->
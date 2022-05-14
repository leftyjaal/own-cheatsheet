# Workflow commands
I use this cheat sheet as referece when im working and forgot some command.
This is going to be updated constantly in time

The idea of this cheatsheet is to have a reference for current and future projects en my carreer

## Table of Contents
  * [1) Conda](#1-conda)
  * [2) Pip](#2-pip)
    

## Conda
**INSTALL Conda on Linux**
```
Go to: https://www.anaconda.com/products/distribution#Downloads 

Copy the linux download hyperlink like:
https://repo.anaconda.com/archive/Anaconda3-2022.05-Linux-x86_64.sh
Type: wget <link>
Type: bash Anaconda*-*-Linux-x86_64.sh
Restart shell or source ~/.bashrc

```
**Create Conda env**
```
conda create --name "env project" python="version"
```
**Remove Conda env**
```
conda env remove --name "env name"
```
**Install & register jupyter Kernel**
```
conda install -c anaconda ipykernel #to install
python -m kernel install --user --name="name" #to register kernel
```
```
ex: 
python -m ipykernel install --user --name tensorflow --display-name "Python 3.8 (tensorflow)"
```
**Create YML file from current env**
```
conda env export > "name".yml
```
**Install Pytorch for GPU**
```
conda install pytorch cudatoolkit -c pytorch
```
**Install CUDAtoolKit and cuDNN**
```
conda install cudatoolkit="11.0" cudnn="8.0" -c=conda-forge
```

## Pip








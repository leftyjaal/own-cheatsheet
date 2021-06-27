# Workflow commands
I use this cheat sheet as referece when im working and forgot some command.
This is going to be updated constantly in time

## Table of Contents
  * [1) Conda](#1-conda)
  * [2) Pip](#2-pip)
    

## Conda
**Create Conda env**
```
conda create --name "env project" python="version"
```
**Remove Conda env**
```
conda env remove --name "env name"
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








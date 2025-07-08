# Acronis Backup


Required software for a standard backup:

## System

- Nvidia Driver
- Python 3.10
- Miniconda
- CUDA 12.6
- CUDNN

## Accessory

- Chrome
- Firefox


## Automation
- TwinCAT
    - Shell
    - Runtime
    - TC1000 ADS
    - TE1300 Scope
    - TF2000 HMI
    - TF 2000 Server
    - Drive Mng 1
    - Drive Mng 2


- .NET 2
- ROBOGUIDE
- Turck Service Tool

## IDE

- VS Code
- Visual Studio 2022

## Utils

- Git (set up key)
- Turtoise SVN
- Set up WD
- WindirStat
- Blender
- Steam
- OBS
- Remote PC
- TeamViewer
- Telegram
- Adobe Pro
- WireShark
- Docker (Possible Conflict with TwinCAT)
- Telegram
- Office
- VLC
- VM Ware
- Virtual Box

## Setup
- Set up ssh key
- Set up cuda paths


## Torch Setup

Create a conda env:

```
conda create --name torch python=3.10
```

Install compatible torch version with CUDA 12.6

```
pip install torch==2.6.0 torchvision==0.21.0 torchaudio==2.6.0 --index-url https://download.pytorch.org/whl/cu126
```

## Jupyter

```
pip install jupyterlab
```

```
pip install notebook
```
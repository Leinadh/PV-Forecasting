# PV-Forecasting

## Installing miniconda3 with python 3.8 on Linux
```shell
sudo apt update
```
```shell
sudo apt upgrade
```
```shell
wget https://repo.anaconda.com/miniconda/Miniconda3-py38_4.10.3-Linux-x86_64.sh
```
```shell
# Verify SHA256 hash with the one in https://docs.conda.io/en/latest/miniconda.html#linux-installers
sha256sum Miniconda3-py38_4.10.3-Linux-x86_64.sh
```
```shell
bash Miniconda3-py38_4.10.3-Linux-x86_64.sh
```

## conda commands
List enviroment packages
```shell
conda list
```
List enviroments
```shell
conda env list
```
Create enviroment
```shell
conda create --name my_env python=3.8.10
```
Activate enviroment
```shell
conda activate my_env
```
Activate enviroment
```shell
conda deactivate 
```

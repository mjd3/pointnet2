# PyTorch Pointnet++

* PyTorch implementation of [PointNet++](https://arxiv.org/abs/1706.02413) based on [sshaoshuai/Pointnet2.PyTorch](https://github.com/sshaoshuai/Pointnet2.PyTorch).
* Supports newer PyTorch versions (>1.0)

## Installation
### Requirements
* Linux (tested on Ubuntu 18.04)
* Python 3.6+
* PyTorch 1.8

### Install
First, install ninja:
```shell
sudo apt-get install ninja-build
```

Then install pytorch:
```shell
pip install torch
```

Install this library by running the following command:
```shell
pip install .
```

## Project using this repo:
* [SceneCollisionNet](https://github.com/mjd3/SceneCollisionNet): Predicts collisions from raw point clouds.

## Acknowledgement
* [charlesq34/pointnet2](https://github.com/charlesq34/pointnet2): Paper author and official code repo.
* [erikwijmans/Pointnet2_PyTorch](https://github.com/erikwijmans/Pointnet2_PyTorch): Initial work of PyTorch implementation of PointNet++.
* [sshaoshuai/Pointnet2.PyTorch](https://github.com/sshaoshuai/Pointnet2.PyTorch): Faster CUDA implementation of Pointnet++.
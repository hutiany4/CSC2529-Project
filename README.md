# CSC2529-Project

course project for CSC2529 at the University of Toronto.

## Overview

This project aims to study and improve the result of the paper [Designing An Illumination-Aware Network for Deep Image Relighting](https://github.com/NK-CS-ZZL/IAN). The original author provides the main structure of the codebase, and we mainly focus on modifying the architectures in the `network/arch` folder.

## Usage

+ We strongly suggested using pre-installed environments such as google collab for this repo
+ If they are not available create the environment by `conda env create -f environment.yml`, but be warned that some conflicts might occur
+ Create `data` folder in the root directory with subfolders `train`, `validation`, and `test`
+ Download dataset from [VIDIT dataset](https://github.com/majedelhelou/VIDIT) and put data into according folders based on option files in `options`
+ Run `python train.py -opt options/[option file]` for training
+ The trained network will be saved to `experiment/[option name]` folder
+ Move the pre-trained network to `pretrained` folder based on option files in `options`
+ Run `python test.py -opt options/[option file]` for testing

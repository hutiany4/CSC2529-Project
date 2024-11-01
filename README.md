# CSC2529-Project

course project for CSC2529 at the University of Toronto.

## Overview

This project aims to study and improve the result of paper [Designing An Illumination-Aware Network for Deep Image Relighting](https://github.com/NK-CS-ZZL/IAN). The code is mainly a clone of the codebase provided by the original author.

## Usage

+ Create the environment by `conda env create -f environment.yml`
+ Create `data` folder in the root directory with subfolders `train`, `validation`, and `test`
+ Download dataset from [VIDIT dataset](https://github.com/majedelhelou/VIDIT) and put data into accordding folders based on option files in `options`
+ Run `python train.py -opt options/[option file]` for train, validation, or test

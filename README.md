# STIDGCN

This is the pytorch implementation of STIDGCN. I hope these codes are helpful to you, 🌟!

<img src="figs/model.pdf" width="75%">

## Requirements
- python
- numpy
- pandas
- torch
- matplotlib
- scipy
- argparse

## Datasets
We provide preprocessed datasets that you can access [here](#). If you need the original datasets, please refer to [STSGCN](https://github.com/Davidham3/STSGCN) (including PEMS03, PEMS04, PEMS07, and PEMS08) and [ESG](https://github.com/LiuZH-19/ESG) (including NYCBike and NYCTaxi).

## Train Commands

### PEMS08
```
nohup python -u train.py --data PEMS08 > PEMS08.log 2>&1 &
```

## Acknowledgments
Our model is built based on model of [Graph WaveNet](https://github.com/nnzhan/Graph-WaveNet) and [SCINet](https://github.com/cure-lab/SCINet).

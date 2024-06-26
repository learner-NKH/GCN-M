### GCN-M: Graph Convolutional Networks for Traffic Forecasting with missing values

This is the companion repository for our paper titled [Graph Convolutional Networks for Traffic Forecasting with missing values](https://link.springer.com/article/10.1007/s10618-022-00903-7) published in [Data Mining and Knowledge Discovery](https://www.springer.com/journal/10618) and also available on [ArXiv](https://arxiv.org/abs/2212.06419).


### Requirements:

- matplotlib == 3.2.1
- numpy == 1.19.2
- pandas == 0.25.1
- scikit_learn == 0.21.2
- torch == 1.6.0
- tensorwatch == 0.9.1

Dependencies can be installed using the following command:

```
pip install -r requirements.txt
```



### Data

Step1: 

- Download METR-LA and PEMS-BAY data from [Google Drive](https://drive.google.com/open?id=10FOTa6HXPqX8Pf5WRoRwcFnW9BrNZEIX) or [Baidu Yun](https://pan.baidu.com/s/14Yy9isAIZYdU__OYEQGa_g) links provided by [DCRNN](https://github.com/liyaguang/DCRNN).
- Put the downloaded data into the repository mentioned in ***"config/DATASET.conf"***

Step2:  Preprocess raw data

```
bash scripts/generate_data.sh
```



### Usage

```
bash scripts/train.sh
```

### Debug

```
bash scripts/debug.sh
```


### Citation

If you find this repository useful in your research, please consider citing the following paper:

```script
@article{zuo2023graph,
  title     = {Graph convolutional networks for traffic forecasting with missing values},
  author    = {Zuo, Jingwei and Zeitouni, Karine and Taher, Yehia and Garcia-Rodriguez, Sandra},
  journal   = {Data Mining and Knowledge Discovery},
  volume    = {37},
  number    = {2},
  pages     = {913--947},
  year      = {2023},
  publisher = {Springer}
}
```

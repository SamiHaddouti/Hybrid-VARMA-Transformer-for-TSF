# Hybrid-VARMA-Transformer-for-TSF

This repository depicts the complete hybrid system surrounding the practical implementation of my bachelor thesis.
It consists of two sub-repositories: 1) [PatchTST](https://github.com/SamiHaddouti/PatchTST) - the modified official sourcecode by [Nie, Yuqi et al. 2023](https://github.com/yuqinie98/PatchTST), 2) [Time Series Library (TSlib)](https://github.com/SamiHaddouti/Time-Series-Library) - a modified library that collect official implementations of advanced time-series forecasting models such as Autoformer, FEDformer, Crossformer, etc. by [Wu, Haixu et al. 2023](https://github.com/thuml/Time-Series-Library)

## Citation:
```
@inproceedings{Yuqietal-2023-PatchTST,
  title     = {A Time Series is Worth 64 Words: Long-term Forecasting with Transformers},
  author    = {Nie, Yuqi and
               H. Nguyen, Nam and
               Sinthong, Phanwadee and 
               Kalagnanam, Jayant},
  booktitle = {International Conference on Learning Representations},
  year      = {2023}
}
```

```
@inproceedings{wu2023timesnet,
  title={TimesNet: Temporal 2D-Variation Modeling for General Time Series Analysis},
  author={Haixu Wu and Tengge Hu and Yong Liu and Hang Zhou and Jianmin Wang and Mingsheng Long},
  booktitle={International Conference on Learning Representations},
  year={2023},
}
```

The core of this repository, is the inference notebook "Hybrid_VARMA_Transformer.ipynb" which includes the EDA, training, evaluation and inference regarding the hybrid system. It was originally run in a Google Colab environment using a GPU.

Parts of the source code were based on the documentation of the libraries used:
- https://pandas.pydata.org/docs (06.05.2023)
- https://numpy.org/doc (06.05.2023)
- https://www.statsmodels.org/stable/ (06.05.2023)
- https://scikit-learn.org/stable/ (06.05.2023)

Functions used for exploratory data analysis such as plotting the distributions of the columns, checking stationarity, and the implementation for the Cointegration, Augmented Dickey Fuller test and Grid Search, were derived from the following sources and modified accordingly:
- https://michael-fuchs-python.netlify.app/2020/10/29/time-series-analysis-regression-extension-techniques-for-forecasting-multivariate-variables/#eda (06.05.2023)
- https://github.com/Apress/hands-on-time-series-analylsis-python/blob/master/Chapter%204/8.%20VARMA%20with%20Gird%20Search.ipynb (06.05.2023)


For a complete picture, draft notebooks, which include pre-assessments like differencing the time-series data or comparing the grid search function against pmdarima.auto_arima, are included. However, they are not directly relevant and therefore not really part of the scope of this work.

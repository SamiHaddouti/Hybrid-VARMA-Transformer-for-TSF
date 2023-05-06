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
- https://pandas.pydata.org/docs
- https://numpy.org/doc
- https://www.statsmodels.org/stable/
- https://scikit-learn.org/stable/

Functions used for exploratory data analysis such as plotting the distributions of the columns, checking stationarity, and the implementation for the Cointegration and Augmented Dickey Fuller test, were derived from the following source and modified accordingly:
- https://michael-fuchs-python.netlify.app/2020/10/29/time-series-analysis-regression-extension-techniques-for-forecasting-multivariate-variables/#eda (06.05.2023)

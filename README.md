# Hybrid-VARMA-Transformer-for-TSF

This repository depicts the complete hybrid system surrounding the practical implementation of my bachelor thesis.
It consists of two sub-repositories: 1) PatchTST - the modified official sourcecode by [Nie, Yuqi et al. 2023](https://github.com/yuqinie98/PatchTST), 2) Time Series Library (TSlib) - a modified library that collect official implementations of advanced time-series forecasting models such as Autoformer, FEDformer, Crossformer, etc. by [Wu, Haixu et al. 2023](https://github.com/thuml/Time-Series-Library)

The core of this repository, is the inference notebook which includes the EDA, training, evaluation and inference regarding the hybrid system. It was originally run in Google Colab.

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


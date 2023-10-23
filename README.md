# Data and Codes for Experimentally Validated Inverse design of Multi-Property Fe-Co-Ni alloys

This repository contains the data and codes for the research work "_**Experimentally Validated Inverse design of Multi-Property Fe-Co-Ni alloys**_" authored by _Shakti P. Padhy, Varun Chaudhary, Yee-Fun Lim, Ruiming Zhu, Muang Thway, Kedar Hippalgaonkar, & Raju V. Ramanujan_ which is currently submitted to Advanced Materials for peer review.

This work addresses the challenge of using incomplete and heterogeneous data in materials science in terms of property measurements and different processing conditions of samples, respectively. A unique method of machine learning-based imputation technique is developed for which the codes are available in the ``2-Imputation`` folder.

The original curated database is present in ``FeNiCo_db_2.csv`` file and the final imputed database is present in ``FeNiCo_comp-prop.csv`` file.

Further, two sets of multi-property models are developed - one with features consisting of only compositional elements and the other with features consisting of compositional elements along with Wen alloy features. The Wen alloy features were calculated using the WenAlloys featurizer class in the matminer package. Further details about these features can be found in the paper "Wen, C., Zhang, Y., Wang, C., Xue, D., Bai, Y., Antonov, S., Dai, L., Lookman, T., & Su, Y. (2019). Machine learning assisted design of high entropy alloys with desired property. Acta Materialia, 170, 109-117."

2 best-performing models were selected and experimental validation of the models was performed.

Lastly, the inverse design of Fe-Co-Ni alloy compositions was done using Bayesian optimization in which multiple property target sets were given. The predicted compositions and predicted property values were also experimentally validated.

All of these codes are available in the ``3-Multi-property ML and multi-objective BO`` folder.

# Cite us
If you used the database or the codes for your research, consider citing our Github repository

```
@dataset{padhy_2023_10032387,
  author       = {Padhy, Shakti Prasad and
                  Chaudhary, Varun and
                  Lim, Yee-Fun and
                  Zhu, Ruiming and
                  Thway, Maung and
                  Hippalgaonkar, Kedar and
                  Ramanujan, Raju V.},
  title        = {{Data and Codes for Experimentally Validated 
                   Inverse design of Multi Property Fe-Co-Ni-alloys}},
  month        = oct,
  year         = 2023,
  publisher    = {Zenodo},
  version      = {v1.0.0},
  doi          = "10.5281/zenodo.10032387"
}
```

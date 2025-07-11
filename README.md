The codes are part of an ongoing thesis of the author and were submitted for publication under the following manuscript title:

**Machine Learning applied to geochemical missing data of the Vaca Muerta Formation: dealing with small sample sizes and heterogeneity**

### Abstract

Missing data is very common in the gas & oil industry, mainly due to mechanical failures or budget limitations. Furthermore, geochemical subsurface studies are frequently conducted during exploratory stages, or sampling is limited to specific zones of interest, resulting in datasets with small sample sizes. Moreover, geochemical analysis can be derived from different laboratories and types of samples, contributing to the heterogeneity of the resultant datasets. This paper evaluates the effectiveness of machine learning in addressing missing X-ray fluorescence (XRF) data for the Vaca Muerta unconventional reservoir located in Argentina. We present two different approaches: 1) Imputation methods to complete geochemical elements in certain depth intervals using a heterogeneous dataset and testing four algorithms: K nearest neighbour (KNN), multiple imputations by chained equations (MICE), miceforest, and MIDAS. 2) Prediction methods to estimate trace element concentrations from major elements using different training wells and comparing four ensemble tree-based algorithms: random forest (RF), extreme gradient boosting (XGBoost), light gradient boosting machine (LightGBM), and Histogram-based Gradient Boosting Regression Tree (HGBT). The imputation results indicated that miceforest outperforms the other algorithms and has the advantage of training and saving the model from datasets with no missing data. The prediction results demonstrated comparable performance across all evaluated algorithms; however, outcomes depend on how adequately the training well sets were selected. Despite the sample size limitations and analytical and geological heterogeneities, the applied imputation and prediction techniques yielded satisfactory performance, as indicated by score metrics and the comparison between the gamma ray log and the gamma ray calculated from K, U, and Th. We emphasise the importance of performing a qualitative assessment instead of solely depending on score metrics and selecting appropriate wells to build an accurate model.

### Highlights

* Multiple imputation and prediction models are proposed to address missing data.
* Miceforest can accurately impute data even when trained on datasets without missing data.
* Tree-based models can correctly predict trace elements in small datasets.
* Selecting suitable wells by considering geological changes is essential to modelling.
* Qualitative assessment is necessary for the final model validation.

### References

The algorithm used in this work can be found in the following references:

1. Chen, T., Guestrin, C., 2016. XGBoost: A Scalable Tree Boosting System. In: The 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD ’16), San Francisco, CA, USA, 785-794. https://doi.org/10.1145/2939672.2939785.
2. Ke, G., Meng, Q., Finley, T., Wang, T., Chen, W., Ma, W., Ye, Q., Liu, T.-Y., 2017. Lightgbm: A highly efficient gradient boosting decision tree. In: Proceedings of the 31st International Conference on Neural Information Processing Systems (NIPS’17), Long Beach, CA, USA, 30, 3149–3157.
3. Lall, R., Robinson, T., 2022. The MIDAS Touch: Accurate and Scalable Missing-Data Imputation with Deep Learning. Political Analysis. 30(2):179-196. https://doi.org/10.1017/pan.2020.49.
4. Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., Blondel, M., Prettenhofer, P., Weiss, R., Dubourg, V., Vanderplas, J., Passos, A., Cournapeau, D., Brucher, M., Perrot, M., Duchesnay, E., 2011. Scikit-learn: Machine Learning in Python. Journal of Machine Learning Research, 12(85), 2825–2830.
5. Wilson, S., 2022. miceforest: Missing Value Imputation Using LightGBM. Python package version 5.6.3, URL https://pypi.org/project/miceforest/.


> [!NOTE]
> The data used in this work are YPF S.A. property and are confidential and, therefore, unavailable for downloading.

# Introduction

* **學期：** 1111
* **課程：** Data Mining
* **描述：** 選擇一篇與Data Mining相關的論文進行實作與實驗
* **Project:** 本團隊選擇「DCF: An Efficient and Robust Density-Based Clustering Method」這篇論文進行實作與實驗


## Set Up

DCFcluster requires the NumPy, SciPy, SciKit Learn, unlzw3 and Itertools libraries to operate. To run the example included, MatPlotLib is also required. 
```bash 
python3 -m pip install numpy
python3 -m pip install scipy
python3 -m pip install scikit-learn
python3 -m pip install unlzw3
```
## Datasets
* Dermatology.data
  * **Description:** Determine the type of Eryhemato-Squamous Disease.
  * **Link:** https://archive.ics.uci.edu/ml/machine-learning-databases/dermatology/dermatology.data

* Ecoli.data
  * **Description:** This data contains protein localization sites.
  * **Link:** https://archive.ics.uci.edu/ml/machine-learning-databases/ecoli/ecoli.data

* Glass.data
  * **Description:** From USA Forensic Science Service; 6 types of glass; defined in terms of their oxide content.
  * **Link:** https://archive.ics.uci.edu/ml/machine-learning-databases/glass/glass.data

* letter-recognition.data
  * **Description:**  Database of character image features; try to identify the letter.
  * **Link:** https://archive.ics.uci.edu/ml/machine-learning-databases/letter-recognition/letter-recognition.data

* wine.data
  * **Description:** Using chemical analysis determine the origin of wines.
  * **Link:** https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data

* bezdekIris.data
  * **Description:** Famous database; from Fisher, 1936
  * **Link:** https://archive.ics.uci.edu/ml/machine-learning-databases/iris/bezdekIris.data

## Run

執行下方程式碼就可以生成資料集，並產生'DCF_Results.csv'，檔案裏面包含六個欄位分別是{method, dataset, k, beta, ARI, AMI}。

```bash 
python3 download_data.py
python3 run_downloaded.py
```


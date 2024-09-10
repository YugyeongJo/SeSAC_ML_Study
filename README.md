# 📚 SeSAC_ML_Study

## 📖 소개

SeSAC ML Study 레포지토리는 학습한 머신러닝 관련 내용을 정리한 것입니다. 주요 개념과 기법들을 다루며, 학습 과정에서 다룬 내용들을 기록하고 있습니다.

### 학습 내용


|구분|학습 내용|
|--|--|
|**데이터 처리**|Pandas를 사용한 데이터 읽기, 관리, 처리 기법 및 DataFrame 조작|
|**데이터 시각화**|Matplotlib과 Seaborn을 활용한 다양한 시각화 기법|
|**머신러닝 기법**|단순 회귀, k-최근접 이웃 분류 및 회귀, 결정 트리, 랜덤 포레스트, 특성 공학|
|**탐색적 데이터 분석**|탐색적 데이터 분석(EDA) 및 통계적 모델링|

## 🛠️ 기술 스택

|<center>VScode</center>|<center>Python</center>|<center>Pandas</center>|<center>Sklearn</center>|<center>Matplotlib</center>|<center>Seaborn</center>|
|--|--|--|--|--|--|
|<p align="center"><img alt="vscode" src="./icons/VSCode-Light.svg" width="48"></p>|<p align="center"><img alt="html" src="./icons/Python-Dark.svg" width="48"></p>|<p align="center"><img alt="html" src="./icons/Pandas.png" width="48"></p>|<p align="center"><img alt="html" src="./icons/ScikitLearn-Dark.svg" width="48"></p>|<p align="center"><img alt="html" src="./icons/matplotlib.png" width="48"></p>|<p align="center"><img alt="html" src="./icons/Seaborn.jpg" width="48"></p>|
|<img src="https://img.shields.io/badge/visual studio code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white">|<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">|<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">|<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">|<img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black">|<img src="https://img.shields.io/badge/Seaborn-%237fb3d5.svg?style=for-the-badge&logo=Seaborn&logoColor=black">|


## 📂 Directory Structure

```plaintext
SeSAC_Database_Study/
├── README.md 
├── Settings_example.ipynb
├── class_file/
│    ├── Data_Handling/
│    │     ├── 01_Readcsv_summary.ipynb
│    │     ├── 02_df_handling_index.ipynb
│    │     ├── 03_df_sorting.ipynb
│    │     ├── 04_df_merge_groupby.ipynb
│    │     ├── Seaborn_01.ipynb
│    │     ├── Seaborn_02.ipynb
│    │     └── Seaborn_03.ipynb
│    └── Machine_Learning/
│          ├── 01_1_단순회귀분석 파라메터 구하기.ipynb
│          ├── 01_2_k최근접분류_표준화.ipynb
│          ├── 01_3_k최근접회귀.ipynb
│          ├── 02_1_결정트리_CV_GrId.ipynb
│          ├── 02_2_랜덤포레스트_GB.ipynb
│          ├── 03_3_특성공학과 규제.ipynb
│          └── ml_part1_pdf/
│                ├── 01_ML Modelling process.pdf
│                └── 02_ML knn_lm_tree.pdf
├── dataset/
│   ├── cars.csv
│   ├── InsectSprays.csv
│   ├── mtcars.xlsx
│   ├── seoul_sgg_list.xlsx
│   ├── seoul_sgg_stat.xlsx
│   ├── stock price.xlsx
│   ├── stock valuation.xlsx
│   ├── ToothGrowth.csv
│   └── 남북한발전전력량.xlsx
└── docs/
    ├── 01_Readcsv.ipynb
    ├── 02_df_handling.ipynb
    ├── 03_df_sorting.ipynb
    ├── 04_df_merger_groupby.ipynb
    ├── 05_Seaborn.ipynb
    ├── titanic_reg.png
    ├──   
    └── 

```

## 💻 File

### 💻 Basic Settings
|번호|구분|파일|설명|비고|
|--|--|--|--|--|
|01|Basic Settings|[Settings_example.ipynb](./Settings_example.ipynb)|기본 환경 세팅||

### 📝 Class File
<details open>
<summary> Data Handling </summary>

|번호|구분|파일|설명|비고|
|--|--|--|--|--|
|01|Data Handling|[01_Readcsv_summary.ipynb](./class_file/Data_Handling/01_Readcsv_summary.ipynb)|Data의 타입과 핸들링 방법 학습||
|02|DataFrame|[02_df_handling_index.ipynb](./class_file/Data_Handling/02_df_handling_index.ipynb)|DataFrame 다루기||
|03|DataFrame Sorting|[03_df_sorting.ipynb](./class_file/03_df_sorting.ipynb)|DataFrame Sorting 방법 학습||
|04|DataFrame Merge|[04_df_merge_groupby.ipynb](./class_file/Data_Handling/04_df_merge_groupby.ipynb)|DataFrame 조작 방법 학습||
|05|Data Visualization|[Seaborn_01.ipynb](./class_file/Data_Handling/Seaborn_01.ipynb)|Seaborn을 활용한 시각화||
|06|Data Visualization|[Seaborn_02.ipynb](./class_file/Data_HandlingSeaborn_02.ipynb)|Seaborn Matplotlib를 통한 시각화||
|07|Data Visualization|[Seaborn_03.ipynb](./class_file/Data_Handling/Seaborn_03.ipynb)|Seaborn Matplotlib를 통한 시각화||
||||||
||||||
||||||

</details>

<details open>
<summary> Machine Learning </summary>

|번호|구분|파일|설명|비고|
|--|--|--|--|--|
|01||[01_1_단순회귀분석 파라메터 구하기.ipynb](./class_file/Machine_Learning/01_1_단순회귀분석%20파라메터%20구하기.ipynb)|||
|02||[01_2_k최근접분류_표준화.ipynb](./class_file/Machine_Learning/01_2_k최근접분류_표준화.ipynb)|||
|03||[01_3_k최근접회귀.ipynb](./class_file/Machine_Learning/01_3_k최근접회귀.ipynb)|||
|04||[02_1_결정트리_CV_GrId.ipynb](./class_file/Machine_Learning/02_1_결정트리_CV_GrId.ipynb)|||
|05||[02_2_랜덤포레스트_GB.ipynb](./class_file/Machine_Learning/02_2_랜덤포레스트_GB.ipynb)|||
|06||[03_3_특성공학과 규제.ipynb](./class_file/Machine_Learning/03_3_특성공학과%20규제.ipynb)|||
||||||
||||||
||||||
||||||
||||||

### 💾 Dataset

<details open>
<summary> Dataset </summary>

|번호|구분|파일|설명|비고|
|--|--|--|--|--|
|01|Dataset|[cars.csv](./dataset/cars.csv)|||
|02|Dataset|[InsectSprays.csv](./dataset/InsectSprays.csv)|||
|03|Dataset|[mtcars.csv](./dataset/mtcars.csv)|||
|04|Dataset|[seoul_sgg_list.csv](./dataset/seoul_sgg_list.csv)|||
|05|Dataset|[seoul_sgg_stat.csv](./dataset/seoul_sgg_stat.csv)|||
|06|Dataset|[stock price.csv](./dataset/stock%price.csv)|||
|07|Dataset|[stock valuation.csv](./dataset/stock%valuation.csv)|||
|08|Dataset|[ToothGrowth.csv](./dataset/ToothGrowth.csv)|||
|09|Dataset|[남북한발전전력량.csv](./dataset/남북한발전전력량.csv)|||
|10|||||
|11|||||
|12|||||

</details>

### 📄 Docs
<details open>
<summary> Docs</summary>

|번호|구분|파일|설명|비고|
|--|--|--|--|--|
|01|File Read|[01_Readcsv.ipynb](./docs/01_Readcsv.ipynb)|file 읽어오기||
|02|DataFrame Handling|[02_df_handling.ipynb](./docs/02_df_handling.ipynb)|DataFrame 조작하기||
|03|DataFrame Sorting|[03_df_sorting.ipynb](./docs/03_df_sorting.ipynb)|DataFrame 정렬하기||
|04|DataFrame Merge|[04_df_merger_groupby.ipynb](./docs/04_df_merger_groupby.ipynb)|DataFrame 합치기||
|05|Data Visualization|[05_Seaborn.ipynb](./docs/05_Seaborn.ipynb)|Seaborn 데이터 시각화||
|06|img|[titanic_reg.png](./docs/titanic_reg.png)|시각화 이미지||

</details>

## 📝참고자료

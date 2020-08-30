# 軟體使用版本
## Main
* Python: 3.6.10
* conda: 4.8.4
## Main Packages
### Data Mining
* Scrapy: 2.3.0
* beautifulsoup4: 4.9.1
### Data Processing
* numpy: 1.19.0
* scipy: 1.5.2
* pandas: 1.1.1
### Machine Learning
* scikit-learn: 0.23.2
* tensorflow-gpu: 1.15.0
* Keras: 2.3.1
### Data Visualization
* seaborn: 0.10.1
* bokeh: 2.2.0
* matplotlib: 3.3.1
* plotly: 4.9.0
### NLP
* ckipnlp: 0.9.1
* ckiptagger: 0.1.1

## Installation
* 建置Python虛擬環境
```
$ conda create -n datathon_2020 python=3.6 
```
* Install Packages (使用 requirements.txt)
```
pip install -r requirements.txt
```
## 註
* tensorflow 依硬體需求選擇安裝 `tensorflow` 或 `tensorflow-gpu`
* `tensorflow-gpu==1.15.0` 需安裝 `CUDA 10.0`
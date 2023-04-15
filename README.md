# practice-analysis

> 회귀, 분류, 시계열을 파이썬과 R을 사용해서 연습해 본 저장소 입니다.

## 설정
* Python <= `3.10.10`
* `numpy`, `pandas`, `matplotlib`는 필수적으로 설치해주세요.
* 고급 시각화를 위해서 `plotly`도 병행해서 사용
* 회귀분석을 위해서 `xgboost`, `Optuna`를 활용
* `ipynb`를 위해서 `JupyterLab`도 함께 설치
* `requirements.txt` 파일을 참고해서 설치 

```shell
$ python -m venv venv
# for Windows
$ .\venv\Scripts\activate
# for Linux/macOS
$ source ./venv/bin/activate
$ (venv) pip install -r requirements.txt
```

## 사용된 패키지 목록
* [numpy](https://numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [seaborn](https://seaborn.pydata.org/)
* [plotly](https://plotly.com/python/)
* [jupyterlab](https://jupyterlab.readthedocs.io/en/stable/)
* [statsmodels](https://www.statsmodels.org/stable/index.html)
* [scikit-learn](https://scikit-learn.org/)
* [xgboost](https://xgboost.readthedocs.io/en/stable/)
* [optuna](https://optuna.readthedocs.io/en/stable/)
* [finance-datareader](https://github.com/financedata-org/FinanceDataReader)
* [prophet](https://facebook.github.io/prophet/docs/quick_start.html)
* [pycountry](https://github.com/flyingcircusio/pycountry)

### TODO 
- [X] 회귀 문제([캘리포니아 집 값 데이터](http://lib.stat.cmu.edu/datasets/))
- [X] 분류 문제([타이타닉 생존자 예측](https://www.kaggle.com/c/titanic))
- [ ] 시계열 문제

### 참고한 GitHub Repository
- [sigmadream/practice-analysis](https://github.com/sigmadream/practice-analysis)

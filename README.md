# practice-analysis

> 회귀, 분류, 시계열을 파이썬과 R을 사용해서 연습해 본 저장소 입니다.

## 설정
* Python <= `3.10.10`
* `numpy`, `pandas`, `matplotlib`는 필수적으로 설치해주세요.
* `ipynb`를 위해서 `JupyterLab`도 함께
```shell
$ python -m venv venv
$ .\venv\Scripts\activate
$ (venv) pip install -r requirements.txt
```
### TODO 
- [ ] 회귀 문제(캘리포니아 집 값 데이터)
- [ ] 분류 문제(타이타닉 생존자 예측, Kaggle)
- [ ] 시계열 문제(문제 탐색 중)

# 2023.04.06
## 프로젝트 시작 시 주의사항

## 파일명과 폴더구조에 대해서
1. 가능하면 영어로 사용
2. 알려진 폴더 구조를 사용

## 매개변수
1. 위치
2. 디폴트 매개변수
3. 이름

## 리스트 vs 튜플
1. 튜플 -> 불변

### 데이터 분석 => Pandas => 데이터 전처리
### 머신러닝 => 사이킷런 => 회귀/분류 => 기울기랑 절편
### 딥러닝 => TF => 회귀/분류 => 기울기랑 절편

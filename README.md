# 주제 : 고혈압을 가진 암환자 사망자 예측
-(고혈압환자의 주요변수의 범위분석)

##  data_a
고혈압인 암환자의 인종,성별,나이,bmi, 칼륨농도, 나트륨농도, 혈압에 따른 사망률과의 관계 시각화 및 구간별 유의성 검정 및 분석

## 분석시 사용한 라이브러리
### pands
### cudf
### numpy
### seaborn
### matplotlib

## 데이터 분석
### 1. 생존, 사망자 분포
### 2. 나이대 별 데이터 분석
### 3. 성별 데이터 분석
### 4. BMI 데이터
### 5. 체내 칼륨과 나트륨 농도 분포
### 6. 혈압에 따른 사망, 생존 분포
### 7. 피어슨 상관계수를 이용한 변수간 상간관계 분석
### 8. 상위 10개 약물 분석

## 사망자 예측 머신러닝 모델 제작
### 1. NaN값 전처리
### 2. 불균형한 라벨 분포 맞춰주기 (under sampling)
### 3. 데이터 스케일링(Robust Scaler 사용)

## 사용한 라이브러리
### sklearn
### cuml

### Gridsearch CV를 이용하여 최적의 하이퍼파라미터를 탐색
### 평가지표
#### f1_score, accuracy 사용

## 사용한 모델
### randomforest
### lightgbm
### adaBoost
### xgboost
### catboost

## 결과
### lightgbm, xgboost AdaBoost 모델의 결과가 좋았음
### 3가지 모델로 hard Voting결과 -> 92%






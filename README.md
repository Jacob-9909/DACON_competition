# 2024 Income Regression

## 프로젝트 개요
이 프로젝트는 소득 예측을 목적으로 하는 회귀 분석 컴페티션입니다. 다양한 머신러닝 모델을 활용하여 개인의 소득을 예측하는 데 중점을 두고 있습니다.

## 사용된 기술 및 모델
- **데이터 전처리**: Pandas, NumPy
- **모델링**: XGBoost, CatBoost, VotingRegressor
- **평가 지표**: RMSE (Root Mean Square Error)

## 필요 패키지
- `pandas`
- `numpy`
- `xgboost`
- `catboost`
- `scikit-learn`
- `jupyter`

## 파일 설명
- `Income_final_df.ipynb`: 데이터 전처리 및 모델 학습
- `catboost + xgboost + VotingRegressor.ipynb`: 다양한 모델을 결합한 VotingRegressor 사용

## 설치 및 사용 방법
1. 필요 패키지 설치
   ```bash
   pip install pandas numpy xgboost catboost scikit-learn jupyter



# 2024 Jeju Product Regression

## 프로젝트 개요
이 프로젝트는 제주도의 상품 판매량을 예측하기 위한 회귀 분석 컴페티션입니다. 여러 변수들을 고려하여 판매량을 정확하게 예측하는 것을 목표로 합니다.

## 사용된 기술 및 모델
- **데이터 전처리**: Pandas, NumPy
- **모델링**: 선형 회귀, Random Forest, Gradient Boosting

## 필요 패키지
- `pandas`
- `numpy`
- `scikit-learn`
- `jupyter`

## 파일 설명
- `jeju_product_final_df.ipynb`: 데이터 전처리 및 모델 학습

## 설치 및 사용 방법
1. 필요 패키지 설치
   ```bash
   pip install pandas numpy scikit-learn jupyter



# 2024 Loan Rating Classification

## 프로젝트 개요
이 프로젝트는 대출 등급 분류를 위한 컴페티션입니다. 대출자의 신용 데이터를 분석하여 대출 등급을 예측하는 데 중점을 두고 있습니다.

## 사용된 기술 및 모델
- **데이터 전처리**: Pandas, NumPy
- **모델링**: 로지스틱 회귀, 랜덤 포레스트, XGBoost
- **평가 지표**: 정확도, F1 스코어

## 필요 패키지
- `pandas`
- `numpy`
- `scikit-learn`
- `xgboost`
- `jupyter`

## 파일 설명
- `loan_rating_final_df.ipynb`: 데이터 전처리 및 모델 학습

## 설치 및 사용 방법
1. 필요 패키지 설치
   ```bash
   pip install pandas numpy scikit-learn xgboost jupyter



# 2024 Weblog Regression

## 프로젝트 개요
이 프로젝트는 웹 로그 데이터를 기반으로 특정 웹사이트의 방문자 수를 예측하는 회귀 분석 컴페티션입니다.

## 사용된 기술 및 모델
- **데이터 전처리**: Pandas, NumPy
- **모델링**: ARIMA, Prophet, LSTM
- **평가 지표**: MSE (Mean Squared Error)

## 필요 패키지
- `pandas`
- `numpy`
- `statsmodels`
- `fbprophet`
- `tensorflow`
- `jupyter`

## 파일 설명
- `web_log_final_df.ipynb`: 데이터 전처리 및 모델 학습

## 설치 및 사용 방법
1. 필요 패키지 설치
   ```bash
   pip install pandas numpy statsmodels fbprophet tensorflow jupyter


# FSI Code Analysis

## 개요
금융 거래 데이터에서 **이상 거래를 탐지하는 기능**을 개선하고 활용도를 높이는 분류 AI모델을 개발하는 것입니다. 
특히, 클래스 불균형 문제를 해결하기 위해 오픈소스 생성형 AI 모델을 활용하여 부족한 클래스의 데이터를 보완하고, 이를 통해 분류 모델의 성능을 향상시키는 것이 핵심 목표입니다. 
이러한 접근을 통해 금융보안에 특화된 데이터 분석 및 활용 역량을 강화하여 전문 인력을 양성하고, 금융권의 AI 활용 어려움에 따른 해결 방안을 함께 모색하며 금융 산업의 AI 활용 활성화를 지원하는 것을 목표로 합니다.

## 사용된 기술 및 모델
- **데이터 전처리**: Pandas, NumPy
- **모델링**: CatBoost, XGBoost, RandomForest
- **평가 지표**: F1 Score

## 필요 패키지
- `pandas`
- `numpy`
- `shap`
- `xgboost`
- `catboost`
- `scipy`
- `optuna`
- `tqdm`
- `sklearn`

## 파일 설명
- `FSI_code.ipynb`: FSI 코드 분석을 위한 주요 노트북 파일로, 데이터 로드부터 결과 해석까지의 전 과정을 포함합니다.

## 설치 및 사용 방법
1. 필요 패키지 설치
   ```bash
   pip install pandas numpy shap xgboost catboost scipy optuna tqdm scikit-learn
   ```


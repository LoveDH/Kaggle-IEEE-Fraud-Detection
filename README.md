# [Kaggle] IEEE-Fraud-Detection

#### 개요
1. [개발환경](#개발환경)
2. [내용](#내용)
3. [파일설명](#파일설명)
4. [결과](#결과)
5. [라이센스 및 저자](#license)

# 개발환경<a name="개발환경"></a>
- Anaconda에서 배포된 Python3 의 라이브러리

- Jupyter Notebook, Kaggle Notebook, Goodle Colaboratory  
  
# 내용<a name="내용"></a>
- 주제 : 효과적인 Machine Learning 모델로 고객의 거래 데이터 중 사기 거래를 탐지

- 데이터 : 전자상거래 결제 솔루션 기업인 Vesta Corporation에서 제공

- 데이터는 고객의 정보부터 거래를 실행한 디바이스까지 다양한 Feature로 구성

Categorical Features - Transaction
* ProductCD
* card1 - card6
* addr1, addr2
* P_emaildomain
* R_emaildomain
* M1 - M9

The TransactionDT feature is a timedelta from a given reference datetime (not an actual timestamp).

Categorical Features - Identity
* DeviceType
* DeviceInfo
* id_12 - id_38

  
# 파일설명<a name="파일설명"></a>

Data는 [Kaggle](https://www.kaggle.com/c/ieee-fraud-detection/data) 에서 참조

EDA Notebook : EDA의 전 과정에 대한 내용을 포함

Features Notebook : 모든 Feature Engeering 내용 포함

Model_baseline : Baseline Model에 대해 작업한 모든 내용을 포함

Model_lgb Notebook : lightgbm 알고리즘에 대한 설명과 lightgbm을 적용한 모델들에 대한 작업 내용 포함

Model_cat Notebook : Catboost 알고리즘에 대한 설명과 Catboost를 적용한 모델에 대한 작업 내용 포함

Model_xgb Notebook : xgboost 알고리즘에 대한 설명과 xgboost를 적용한 모델에 대한 작업 내용 포함

Model_blend : 모델들을 Blending 한 내용을 포함


# 결과<a name="결과"></a>
최고 성적으로 LB AUC 0.952007 , PB AUC 0.928689 을 기록

  
# 라이센스 및 저자<a name="license"></a>
Data Source는 [Kaggle](https://www.kaggle.com/c/home-credit-default-risk/data) 에 포함

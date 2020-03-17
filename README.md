# [Kaggle] IEEE-Fraud-Detection

#### 개요
1. [개발환경](#개발환경)
2. [내용](#내용)
3. [파일설명](#파일설명)
4. [결과] (#결과)
5. [라이센스 및 저자](#라이센스 및 저자)

# 개발환경<a name="개발환경"></a>
- Anaconda에서 배포된 Python3 의 Librarys
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

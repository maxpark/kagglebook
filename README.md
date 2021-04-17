# kagglebook
 
### 이 책에서의 라이브러리 버전 정보(실행 확인 2021.03)
 - 파이썬 버전 :  3.8.5 (default, Sep  3 2020, 21:29:08) [MSC v.1916 64 bit (AMD64)]
 - 팬더스 버전 :  1.2.2
 - matplotlib 버전 :  3.3.4
 - 넘파이 버전 :  1.19.5
 - scikit-learn 버전 :  0.24.1
 - tensorflow 버전 :  2.4.1
 - 케라스 버전 :  2.4.3
 - xgboost 버전 :  1.3.3
 - lightgbm 버전 :  3.1.1
 - hyperopt 버전 :  0.2.5
 - 일부 라이브러리 버전이 맞지 않을 경우, 소스코드 일부가 실행이 되지 않을 수 있습니다. 

### 환경 준비(Window용) [Link](https://ldjwj.github.io/kagglebook/pdf_html/1_1_env.html)
### 환경준비(MAC용)
 - (추가 예정)
### 환경준비(Linux용)
 - (추가 예정)

 - [설치 영상 추가 예정] [아나콘다 설치](Link1) [가상환경설치](Link2) [Pycharm 설치 및 소스코드 불러오기](Link3)


### 일부 유저에 소스 코드 실행 이슈가 있음.
 - bhtsne 모듈 설치가 안되는 이슈(2021.03.13) - 버전 불일치로 판단됨.

## 소스 코드 보기
 - [캐글의 노트북 환경에서 시작하기] [유튜브-추가계획]() [네이버tv-추가계획]() 
 ### ch01 - 타이타닉 대회

 ### ch02
   * 파이썬 소스 코드보기

|파일명|code(.py)|code(.ipynb)|
|------|---|---|
|ch02-01-metrics        |[CODE(.py)](https://github.com/LDJWJ/kagglebook/blob/main/ch02/ch02-01-metrics.py)|[CODE(노트북)](https://ldjwj.github.io/kagglebook/code_with_jupyter/ch02/ch02-01-metrics.html)|
|ch02-02-custom-usage   |[CODE(.py)](https://github.com/LDJWJ/kagglebook/blob/main/ch02/ch02-02-custom-usage.py)|[CODE(노트북)](https://ldjwj.github.io/kagglebook/code_with_jupyter/ch02/ch02-02-custom-usage.html)|
|ch02-03-optimize       |[CODE(.py)](https://github.com/LDJWJ/kagglebook/blob/main/ch02/ch02-03-optimize.py) |[CODE(노트북)](https://ldjwj.github.io/kagglebook/code_with_jupyter/ch02/ch02-03-optimize.html)|
|ch02-04-optimize-cv    |[CODE(.py)](https://github.com/LDJWJ/kagglebook/blob/main/ch02/ch02-04-optimize-cv.py)|[CODE(노트북)](https://ldjwj.github.io/kagglebook/code_with_jupyter/ch02/ch02-04-optimize-cv.html)|
|ch02-05-custom-function|[CODE(.py)](https://github.com/LDJWJ/kagglebook/blob/main/ch02/ch02-05-custom-function.py)| [CODE(노트북)](https://ldjwj.github.io/kagglebook/code_with_jupyter/ch02/ch02-05-custom-function.html)|

 - ch03 - *** 대회

 - ch04 - *** 대회

 - ch05 - *** 대회

 - ch06 - *** 대회

 - ch07 - *** 대회
 



## 책에서의 관련 캐글 대회 및 정보 링크

#### ch01
  - 대회의 상위 솔루션 정리 [by sudalairajkumar](https://www.kaggle.com/sudalairajkumar/winning-solutions-of-kaggle-competitions)
  - 타이타닉 대회의 솔루션 정리 [by pliptor](https://www.kaggle.com/pliptor/how-am-i-doing-with-my-score)

#### ch02
 ### 평가지표로 보는 캐글 대회
   - Instacart Market Basket Analysis [대회로](https://www.kaggle.com/c/allstate-claims-severity)
    - 내용 : 보험 청구는 얼마나 심각한지에 대한 정도의 예측
    - 평가지표 : 평가지표(MAE)
 
  - Instacart Market Basket Analysis [대회로](https://www.kaggle.com/c/human-protein-atlas-image-classification/)
    - 내용 : Instacart 소비자는 어떤 제품을 다시 구매할까?
    - 평가지표 : 평가지표(mean F1 score)
    
  - Santander Product Recommendation [대회로](https://www.kaggle.com/c/santander-product-recommendation)
    - 내용 :Santander Bank  는 개인화 된 제품 추천 
    - 평가지표 : MAP@7 (Mean Average Precision @ 7)

  - Human Protein Atlas Image Classification [대회로](https://www.kaggle.com/c/hpa-single-cell-image-classification)
    - 내용 : 현미경 이미지에서 개별 인간 세포 차이 찾기 (다중 레이블 분류 문제)
    - 평가지표 : Macro F-Score

  - Quora Question Pairs 대회 [대회로](https://www.kaggle.com/c/quora-question-pairs)
    - 내용 : 같은 의도를 가진 질문 쌍을 식별하기
    - 평가지표 : 로그 손실

  - Home Credit Default Risk 대회 [대회로](https://www.kaggle.com/c/home-credit-default-risk)
    - 내용 : 각 신청자가 대출금을 상환 할 수있는 능력을 예측
    - 평가지표 : AUC

  - Two Sigma Connect: Rental Listing Inquiries [대회로](https://www.kaggle.com/c/two-sigma-connect-rental-listing-inquiries)
    - 내용 : RentHop의 새 임대 목록에 대한 관심은 얼마나됩니까?
    - 평가지표 : multi-class logloss
   
  - Bosch Production Line Performance [대회로](https://www.kaggle.com/c/bosch-production-line-performance)
    - 내용 : 제조 프로세스 개선을 위한 제조 실패 감소
    - 평가지표 : MCC
    - 
### 시계열 데이터를 다루는 대회
 - Recruit Restaurant Visitor forecasting 대회  [대회로](https://www.kaggle.com/c/recruit-restaurant-visitor-forecasting)
   - 내용 : 각 음식점의 일별 손님 수를 알려주고 미래의 손님 수를 예측
 - Santander Product Recommendation 대회 [대회로](https://www.kaggle.com/c/santander-product-recommendation)
   - 내용 : 각 고객의 금융상품 구매 이력을 월 단위로 제공하고 가장 최근 월의 구매상품을 예측
 - Two Sigma financial modeling Challenge 대회 [대회로](https://www.kaggle.com/c/two-sigma-financial-modeling)
   - 내용 : 금융 시장의 특징이 익명화된 시계열 데이터를 주고 지정된 특징의 미래 값을 예측
 - Coupon Purchase Prediction 대회 [대회로](https://www.kaggle.com/c/coupon-purchase-prediction)
   - 내용 : 공동구매형 쿠폰 사이트의 사용자와 과거에 판매된 쿠폰 및 구매 이력 등의 정보를 주고 미래에 각 사용자가 어떤 쿠폰을 구매할지 예측
  
  - 기타 대회
    - 자연어 처리 대회 - Quora Question Pairs 대회
    - 정형 데이터와 광고 이미지 함께 분석 - Avito Demand Prediction Challenge 대회
   
 ### 상위 솔루션
  - Allstate Claims Severity Competition, 2nd Place Winner’s Interview: Alexey Noskov [이동](https://medium.com/kaggle-blog/allstate-claims-severity-competition-2nd-place-winners-interview-alexey-noskov-f4e4ce18fcfc)
  - Home Credit Default Risk - 2nd place solution [이동](https://speakerdeck.com/hoxomaxwell/home-credit-default-risk-2nd-place-solutions?slide=11)

#### ch03
  - [Instacart Market Basket Analysis 2nd place solution](https://www.slideshare.net/kazukionodera7/kaggle-meetup-3-instacart-2nd-placesolution) 
    - 최근 주문 여부를 보여주는 배열을 주고, 가장 최근 기록부터 중요도를 매개 수치로 변환하는 기술 활용
    - 아이템 특별 상품에 주목 - 유기농, 글루텐, 아시아의 아이템에 주목
  - 와이드 포맷 자료 [Link1](https://www.datacamp.com/community/tutorials/long-wide-data-R) [Link2](https://seananderson.ca/2013/10/19/reshape/)
  - Porto Seguro’s Safe Driver Prediction 대회의 1위 솔루션 [Link](https://www.kaggle.com/c/porto-seguro-safe-driver-prediction/discussion/44629)
    - 잡음 제거 오토 인코더 사용 
  - 실제로 캐글 Allstate Claims Severity 대회의 2위 솔루션 [Link](https://medium.com/kaggle-blog/allstate-claims-severity-competition-2nd-place-winners-interviewalexey-noskov-f4e4ce18fcfc)
    - 클러스터 중심으로부터 거리를 특징으로 사용
  - 사이킷런의 cluster 모듈 [Link](https://scikit-learn.org/stable/modules/clustering.html)
  - 여러 변수를 조합한 지수 사용 - Recruit Restaurant Visitor Forecasting 대회 20th Solution [Link](https://www.kaggle.com/c/recruit-restaurant-visitor-forecasting/discussion/49328)
  - Avito Demand Prediction Challenge 대회 9위 솔루션 (https://www.slideshare.net/JinZhan/kaggle-avito-demand-prediction-challenge-9th-place-solution-124500050)
     - 중요한 변수인 가격에 대해 상품명, 상품 분류(카테고리), 사용자나 지역 등 다양한 관점에서 평균과의 차와 비율 확인
     
#### ch04

#### ch05

#### ch06

#### ch07

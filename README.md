# Machine_Learning
💻 파이썬 머신러닝 완벽 가이드 👩‍💻
---
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FLee-HyeongBin%2FMachine_Learning&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
---
<b>Since</b> 2021.03.15 ~ ing
---
* 머신러닝의 기본인 지도 학습, 비지도 학습, 평가, 최적화 등 학습
* 파이썬 머신러닝 완벽 가이드 책 사용
* 각 코드 내, 마크다운과 주석을 통하여 설명

<br><br><br>
# 📃 Table of Contents
## 1장: 파이썬 기반의 머신러닝과 생태계 이해
* 머신러닝의 개념
* __머신러닝의 분류
* __데이터 전쟁
* __파이썬과 R 기반의 머신러닝 비교
* 파이썬 머신러닝 생태계를 구성하는 주요 패키지
* __파이썬 머신러닝을 위한 S/W 설치
* 넘파이
* __넘파이 ndarray 개요
* __ndarray의 데이터 타입
* __ndarray를 편리하게 생성하기 - arange, zeros, ones
* __ndarray의 차원과 크기를 변경하는 reshape( )
* __넘파이의 ndarray의 데이터 세트 선택하기 - 인덱싱(Indexing)
* __행렬의 정렬 - sort( )와 argsort( )
* __선형대수 연산 - 행렬 내적과 전치 행렬 구하기
* 데이터 핸들링 - 판다스
* __판다스 시작 - 파일을 DataFrame으로 로딩, 기본 API
* __DataFrame과 리스트, 딕셔너리, 넘파이 ndarray 상호 변환
* __DataFrame의 컬럼 데이터 세트 생성과 수정
* __DataFrame 데이터 삭제
* __Index 객체
* __데이터 셀렉션 및 필터링
* __정렬, Aggregation 함수, GroupBy 적용
* __결손 데이터 처리하기
* __apply lambda 식으로 데이터 가공
* 정리<br><br>
## 2장: 사이킷런으로 시작하는 머신러닝
### 2.1. 사이킷런 소개와 특징
### 2.2. 첫 번째 머신러닝 만들어 보기 - 붓꽃 품종 예측하기
### 2.3. 사이킷런의 기반 프레임워크 익히기
* __Estimator 이해 및 fit( ), predict( ) 메서드
* __사이킷런의 주요 모듈
* __내장된 예제 데이터 세트
### 2.4. Model Selection 모듈 소개
* __학습/테스트 데이터 세트 분리 - train_test_split()
* __교차 검증
* __GridSearchCV - 교차 검증과 최적 하이퍼 파라미터 튜닝을 한 번에
### 2.5. 데이터 전처리
* __데이터 인코딩
* __피처 스케일링과 정규화
* __StandardScaler
* __MinMaxScaler
### 2.6. 사이킷런으로 수행하는 타이타닉 생존자 예측
### 2.7. 정리<br><br>
## 3장: 평가
### 3.1. 정확도(Accuracy)
### 3.2. 오차 행렬
### 3.3. 정밀도와 재현율
* __정밀도/재현율 트레이드오프
* __정밀도와 재현율의 맹점
### 3.4. F1 스코어
### 3.5. ROC 곡선과 AUC
### 3.6. 피마 인디언 당뇨병 예측
### 3.7. 정리<br><br>
## 4장: 분류
### 4.1. 분류(Classification)의 개요
### 4.2. 결정 트리
* __결정 트리 모델의 특징
* __결정 트리 파라미터
* __결정 트리 모델의 시각화
* __결정 트리 과적합(Overfitting)
* __결정 트리 실습 - 사용자 행동 인식 데이터 세트
### 4.3. 앙상블 학습
* __앙상블 학습 개요
* __보팅 유형 - 하드 보팅(Hard Voting)과 소프트 보팅(Soft Voting)
* __보팅 분류기(Voting Classifier)
### 4.4. 랜덤 포레스트
* __랜덤 포레스트의 개요 및 실습
* __랜덤 포레스트 하이퍼 파라미터 및 튜닝
### 4.5. GBM(Gradient Boosting Machine)
* __GBM의 개요 및 실습
* __GBM 하이퍼 파라미터 및 튜닝
### 4.6. XGBoost(eXtra Gradient Boost)
* __XGBoost 개요
* __XGBoost 설치하기
* __파이썬 래퍼 XGBoost 하이퍼 파라미터
* __파이썬 래퍼 XGBoost 적용 - 위스콘신 유방암 예측
* __사이킷런 래퍼 XGBoost의 개요 및 적용
### 4.7. LightGBM
* __LightGBM 설치
* __LightGBM 하이퍼 파라미터
* __하이퍼 파라미터 튜닝 방안
* __파이썬 래퍼 LightGBM과 사이킷런 래퍼 XGBoost,
* __LightGBM 하이퍼 파라미터 비교
* __LightGBM 적용 - 위스콘신 유방암 예측
### 4.8. 분류 실습 - 캐글 산탄데르 고객 만족 예측
* __데이터 전처리
* __XGBoost 모델 학습과 하이퍼 파라미터 튜닝
* __LightGBM 모델 학습과 하이퍼 파라미터 튜닝
### 4.9. 분류 실습 - 캐글 신용카드 사기 검출
* __언더 샘플링과 오버 샘플링의 이해
* __데이터 일차 가공 및 모델 학습/예측/평가
* __데이터 분포도 변환 후 모델 학습/예측/평가
* __이상치 데이터 제거 후 모델 학습/예측/평가
* __SMOTE 오버 샘플링 적용 후 모델 학습/예측/평가
### 4.10. 스태킹 앙상블
* __기본 스태킹 모델
* __CV 세트 기반의 스태킹
### 4.11. 정리<br><br>
## 5장: 회귀
### 5.1. 회귀 소개
### 5.2. 단순 선형 회귀를 통한 회귀 이해
### 5.3. 비용 최소화하기 - 경사 하강법(Gradient Descent) 소개
### 5.4. 사이킷런 LinearRegression을 이용한 보스턴 주택 가격 예측
* __LinearRegression 클래스 - Ordinary Least Squares
* __회귀 평가 지표
* __LinearRegression을 이용해 보스턴 주택 가격 회귀 구현
### 5.5. 다항 회귀와 과(대)적합/과소적합 이해
* __다항 회귀 이해
* __다항 회귀를 이용한 과소적합 및 과적합 이해
* __편향-분산 트레이드오프(Bias-Variance Trade off)
### 5.6. 규제 선형 모델 - 릿지, 라쏘, 엘라스틱넷
* __규제 선형 모델의 개요
* __릿지 회귀
* __라쏘 회귀
* __엘라스틱넷 회귀
* __선형 회귀 모델을 위한 데이터 변환
### 5.7. 로지스틱 회귀
### 5.8. 회귀 트리
### 5.9. 회귀 실습 - 자전거 대여 수요 예측
* __데이터 클렌징 및 가공
* __로그 변환, 피처 인코딩과 모델 학습/예측/평가
### 5.10. 회귀 실습 - 캐글 주택 가격: 고급 회귀 기법
* __데이터 사전 처리(Preprocessing)
* __선형 회귀 모델 학습/예측/평가
* __회귀 트리 모델 학습/예측/평가
* __회귀 모델의 예측 결과 혼합을 통한 최종 예측
* __스태킹 앙상블 모델을 통한 회귀 예측
### 5.11. 정리<br><br>
## 6장: 차원 축소
### 6.1. 차원 축소(Dimension Reduction) 개요
### 6.2. PCA(Principal Component Analysis)
* __PCA 개요
### 6.3. LDA(Linear Discriminant Analysis)
* __LDA 개요
* __붓꽃 데이터 세트에 LDA 적용하기
### 6.4. SVD(Singular Value Decomposition)
* __SVD 개요
* __사이킷런 TruncatedSVD 클래스를 이용한 변환
### 6.5. NMF(Non-Negative Matrix Factorization)
* __NMF 개요
### 6.6. 정리<br><br>
## 7장: 군집화
### 7.1. K-평균 알고리즘 이해
* __사이킷런 KMeans 클래스 소개
* __K-평균을 이용한 붓꽃 데이터 세트 군집화
* __군집화 알고리즘 테스트를 위한 데이터 생성
### 7.2. 군집 평가(Cluster Evaluation)
* __실루엣 분석의 개요
* __붓꽃 데이터 세트를 이용한 군집 평가
* __군집별 평균 실루엣 계수의 시각화를 통한 군집 개수 최적화 방법
### 7.3. 평균 이동
* __평균 이동(Mean Shift)의 개요
### 7.4. GMM(Gaussian Mixture Model)
* __GMM(Gaussian Mixture Model) 소개
* __GMM을 이용한 붓꽃 데이터 세트 군집화
* __GMM과 K-평균의 비교
### 7.5. DBSCAN
* __DBSCAN 개요
* __DBSCAN 적용하기 - 붓꽃 데이터 세트
* __DBSCAN 적용하기 - make_circles( ) 데이터 세트
### 7.6. 군집화 실습 - 고객 세그먼테이션
* __고객 세그먼테이션의 정의와 기법
* __데이터 세트 로딩과 데이터 클렌징
* __RFM 기반 데이터 가공
* __RFM 기반 고객 세그먼테이션
### 7.7. 정리<br><br>
## 8장: 텍스트 분석
* NLP이냐 텍스트 분석이냐?
### 8.1. 텍스트 분석 이해
* __텍스트 분석 수행 프로세스
* __파이썬 기반의 NLP, 텍스트 분석 패키지
### 8.2. 텍스트 사전 준비 작업(텍스트 전처리) - 텍스트 정규화
* __클렌징
* __텍스트 토큰화
* __스톱 워드 제거
* __Stemming과 Lemmatization
### 8.3. Bag of Words - BOW
* __BOW 피처 벡터화
* __사이킷런의 Count 및 TF-IDF 벡터화 구현: CountVectorizer, TfidfVectorizer * __BOW 벡터화를 위한 희소 행렬
* __희소 행렬 - COO 형식
* __희소 행렬 - CSR 형식
### 8.4. 텍스트 분류 실습 - 20 뉴스그룹 분류
* __텍스트 정규화
* __피처 벡터화 변환과 머신러닝 모델 학습/예측/평가
* __사이킷런 파이프라인(Pipeline) 사용 및 GridSearchCV와의 결합
### 8.5. 감성 분석
* __감성 분석 소개
* __지도학습 기반 감성 분석 실습 - IMDB 영화평
* __비지도학습 기반 감성 분석 소개
* __SentiWordNet을 이용한 감성 분석
* __VADER를 이용한 감성 분석
### 8.6. 토픽 모델링(Topic Modeling) - 20 뉴스그룹
### 8.7. 문서 군집화 소개와 실습(Opinion Review 데이터 세트)
* __문서 군집화 개념
* __Opinion Review 데이터 세트를 이용한 문서 군집화 수행하기
* __군집별 핵심 단어 추출하기
### 8.8. 문서 유사도
* __문서 유사도 측정 방법 - 코사인 유사도
* __두 벡터 사잇각
* __Opinion Review 데이터 세트를 이용한 문서 유사도 측정
### 8.9. 한글 텍스트 처리 - 네이버 영화 평점 감성 분석
* __한글 NLP 처리의 어려움
* __KoNLPy 소개
* __데이터 로딩
### 8.10. 텍스트 분석 실습-캐글 Mercari Price Suggestion Challenge
* __데이터 전처리
* __피처 인코딩과 피처 벡터화
* __릿지 회귀 모델 구축 및 평가
* __LightGBM 회귀 모델 구축과 앙상블을 이용한 최종 예측 평가
### 8.11. 정리<br><br>
## 9장: 추천 시스템
### 9.1. 추천 시스템의 개요와 배경
* __추천 시스템의 개요
* __온라인 스토어의 필수 요소, 추천 시스템
* __추천 시스템의 유형
### 9.2. 콘텐츠 기반 필터링 추천 시스템
### 9.3. 최근접 이웃 협업 필터링
### 9.4. 잠재 요인 협업 필터링
* __잠재 요인 협업 필터링의 이해
* __행렬 분해의 이해
* __확률적 경사 하강법을 이용한 행렬 분해
### 9.5. 콘텐츠 기반 필터링 실습 - TMDB 5000 영화 데이터 세트
* __장르 속성을 이용한 영화 콘텐츠 기반 필터링
* __데이터 로딩 및 가공
* __장르 콘텐츠 유사도 측정
* __장르 콘텐츠 필터링을 이용한 영화 추천
### 9.6. 아이템 기반 최근접 이웃 협업 필터링 실습
* __데이터 가공 및 변환
* __영화 간 유사도 산출
* __아이템 기반 최근접 이웃 협업 필터링으로 개인화된 영화 추천
### 9.7. 행렬 분해를 이용한 잠재 요인 협업 필터링 실습
### 9.8. 파이썬 추천 시스템 패키지 - Surprise
* __Surprise 패키지 소개
* __Surprise를 이용한 추천 시스템 구축
* __Surprise 주요 모듈 소개
* __Surprise 추천 알고리즘 클래스
* __베이스라인 평점
* __교차 검증과 하이퍼 파라미터 튜닝
* __Surprise를 이용한 개인화 영화 추천 시스템 구축
### 9.9. 정리
<br><br>
## Reference
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[교재 링크](http://www.yes24.com/Product/Goods/69752484)<br>
![image](http://image.yes24.com/goods/69752484/800x0)

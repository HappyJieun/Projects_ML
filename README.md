# Projects_ML

머신러닝 프로젝트 설명서

***

 # 1. Fitbit 생체시계 설문조사 데이터 전처리 
  2021.12 ~ 2022.01 / R, Linux / Team project

- Background 
  <p> 청소년기의 생체리듬이 신체와 정신 건강에 미치는 영향을 확인하고자 함. 일상 생활에서의 활동량, 수면 패턴, 심박수 등의 건강 관련 데이터를 모니터링할 수 있는 웨어러블 기기인 Fitbit의 데이터를 이용함. </p>

- Summary
 
	(1) Data Collection
    - https://nda.nih.gov/data-structure/abcd_fbdpas01
  
	(2) Contribution
    - Fitbit 이용자의 설문 조사 데이터 전처리 및 시각화 담당

    - 전처리: Variable Selection, correlation coefficient
 
    - 시각화: Daily physical activity summaries
    
  (3) Result & Lesson
    - Fitbit 데이터와 설문조사 데이터를 병합하여 빅데이터 형성
    
    - 설문조사 정보와 실제 데이터 간의 연관성 발견
    
    - 시각화 지표 153개 생성
  
- 보러가기: [Link](https://github.com/HappyJieun/ABCD)

 ***
 
 # 2. 미생물 빅데이터를 이용한 질병 예측 모델 개발 
  2022.02 ~ 2022.05 / R, Linux / Personal project

- Background 
  <p> 정상인과 특정 질병을 가진 사람의 미생물에 큰 차이가 있음이 밝혀지면서 MGnify 데이터베이스로부터 다양한 질병군의 미생물 자료를 수집하여 질병을 동시에 분류할 수 있는 질병 예측 모델을 개발하고자 함. </p>

- Summary
 
	(1) Data Collection
    - MGnify database 
  
	(2) Contribution
    - 미생물 데이터 수집 및 전처리 (23가지 질병)
      
    - Txanomy 기반 5개의 빅데이터 형성
      
    - 질병 외 외부 환경 변수 통제를 위한 차원 축소, 군집화 진행
      
    - Randomforest, KNN, SVM 등 5가지의 분류 알고리즘 적용
    
  (3) Result & Lesson
    - 최적의 모델 선정 및 평균 85% 이상의 정확도
      
    - endometrial cancer, benign uterine condition 와 같이 유사한 질병의 경우 예측 어려움
 
    - 병렬 처리
  
  
- 보러가기: [Link](https://github.com/HappyJieun/Microbiome)

 ***
 
 # 3. 고차원 생체 데이터 기반 개인 맞춤형 심장병 예측 모델 개발
  2023.09 ~ 2023.11 / Python / Team project

- Background 
  <p> 진단의 복잡성과 조기 진단의 중요성을 지닌 심장병을 생체 데이터를 이용하여 정확하고 효율적으로 진단하고자 함. </p>

- Summary
 
	(1) Data Collection
    - UCI database 
  
	(2) Contribution
    - 데이터 선정 및 수집
    
    - 시각화 및 전처리 (Variable selection)
      
    - 머신러닝 모델 적용 및 Hyper Parameters 튜닝
    
  (3) Result & Lesson
    - 최적의 모델 선정 및 평균 90% 이상의 정확도 확인
    
    - 심장병 진단 주요 지표 확인
    
    - 심장병 주요 발병 군집 확인
  
  
- 보러가기: [Link](https://github.com/HappyJieun/HeartBeat) (비공개)

 ***
 
 # 4. 생체 신호 데이터를 이용한 흡연 여부 예측 모델링
  2023.11 ~ 2024.02 / R / Team project

- Background 
  <p> 흡연자의 생체 신호 데이터 분석을 통해 흡연과 관련된 주요 위험 요인들을 식별하고 개인화된 예방 및 치료 계획을 수립하고자 함. </p>

- Summary
 
	(1) Data Collection
    - Kaggle
  
	(2) Contribution
    - 데이터 선정 및 수집
    
    - 시각화 및 전처리: IQR,  Variable selection
    
    -  K-fold cross validation 모델링
    
  (3) Result & Lesson
    - 흡연의 위험 요인 확인
    
    - 특정 질병 유발 생체 신호 확인
      
    - 정확도 향상을 위한 튜닝이 필요함
  
  
- 보러가기: [Link](https://github.com/HappyJieun/Smoking)

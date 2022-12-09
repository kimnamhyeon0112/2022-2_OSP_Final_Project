# 2022-2_OSP_Final_Project
## 프로젝트 소개 ##
이 프로젝트는 2022년 2학년 2학기 오픈소스개발프로젝트 기말 프로젝트입니다.

## 개요 ##
2022 카타르 월드컵 우승 국가 예측

## 개발 기간 ##
2022.12.01 ~ 2022.12.06

### 개발 환경 ###
  - Jupyter Notebook

### 사용 툴 ###
  - Visual Studio Code

### 사용 방법 ###
  - pip install pandas
  - pip install numpy
  - pip install matplotlib
  - pip install seaborn
  - pip install skikit-learn

### 데이터 수집 ###
Soccer World Cup 2022 Prediction(https://www.kaggle.com/datasets/shilongzhuang/soccer-world-cup-challenge) 

### 데이터 분석 ###
1. groupby를 사용한 데이터 그룹화 후 간단한 통계분석
    - 2022_world_cup_groups.csv파일에서 그룹으로 묶어 총 A~H조 까지 그룹화
2. matplotlib을 활용한 그래프 2가지 그리기
    - 2022년 카타르 월드컵에 참가하는 32개국의 1800년 이후부터 모든 경기의 승/패/무승부를 막대그래프로 표현
    - 조별로 역대 승률을 파이 차트로 표현
3. 머신러닝 기법을 1개 이상 사용하여 모델 학습 및 모델 평가 수치 계산

### 결과 해석 및 응용 방향 설계 ###
이번 프로젝트에서는 우승 국가만 예측했는데, 임의의 국가를 입력하면 해당 국가의 최종 성적이 어느 정도일지 예측하는 방안도 고려하는 것도 괜찮은 선택

ex) 대한민국 -> 16강

앱 개발시 현 프로젝트를 보완하여 유저가 직접 대진표를 짜보고, 메신저 앱(ex 카카오톡, 인스타그램 DM 등)으로 공유할 수 있게 하는 앱을 제작

### 보고서 ###
[2019037004_김남현_오픈소스기말프로젝트](*2019037004_김남현_오픈소스기말프로젝트).docx 참고
## 데잇걸즈 4기

## 팀원
김새민, 김주현, 이다슬, 정희경, 최하나

## 프로젝트 이름  
호텔 리뷰 맛집 여기 있어요!

## 프로젝트 개요
호텔 예약 사이트의 리뷰 중 "좋아요", "굿", "별로에요" 같은 리뷰 말고, 실제로 호텔 예약에 도움되는 리뷰의 특징은 무엇일까? 
도움되는 리뷰 순으로 정렬할 수 있는 새로운 리뷰 정렬 모델을 제안합니다.

***

## 작업 과정 설명
**1. Web Scrapping**
- 호텔 예약 사이트 웹 스크래핑(크롤링) 코드
  - [야놀자](1_crawling_yanolja.html)
  - [아고다](1_crawling_agoda.html)
  - [여기어떄](1_crawling_goodchoice.html)
  
**2. Preprocessing**
- 데이터 전처리 관련 코드
  - [전처리](2_preprocessing.html)
 
**3. Visualization**
- 아래 기준으로 분류 라벨링 작업을 진행하고, 그 데이터로 시각화를 시도한 코드
  (1) 도움되는 리뷰 & 도움되지 않는 리뷰 (2) 긍정 & 부정 & 중립 (3) 시설 & 위치 & 인테리어 & 친절 & 청결 & 방음
- Excel, Tableau, Python(Plotly) 사용
  - [키워드 별 빈도수](3_visualization_keyword_frequency.html)
  - [키워드 별 긍정/부정 비율](3_visualization_keyword_attitude.html)
  - [Tableau](3_visualization_by_tableau.html)
  - [Boxplot](3_visualization_boxplot.html)
  - [Network Map](3_visualization_network_map.html)
  - [시각화 이미지만 모아보기](3_visualization_img_only.html)


**4. Modeling**
- 라벨링 작업 후 분류 모델링 및 confusion matrix로 평가한 코드 
  - [Scikit-Learn](4_modeling_scikit-learn_logistic_regression.html)
  - [Tensorflow](4_modeling_tensorflow_sequential.html)
  
**Data**
- 특수문자, 이모티콘, 개행문자 등을 제거하고 맞춤법을 올바르게 수정해 전처리된, 분석에 사용된 Law data입니다. [링크](https://github.com/dataitgirls4/team_4/tree/main/data)

***

## 최종 발표 자료
[링크](https://bit.ly/newgoldhotel)

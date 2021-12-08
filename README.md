# 서울시 따릉이 자전거 이용 예측 AI모델
* 대회 주제 : 공공 빅데이터인 서울시 따릉이 데이터를 이용하여 인공지능 모델 개발
* 대회 개요 : 각 날짜의 1시간 전의 기상상황을 토대로 1시간 후의 따릉이 대여수 예측
* 대회 일정 : 기간 제한 없음
* 평가 지표 : RMSE 
* 분석 도구 : python
* 활용 모델 : 선형회귀, 랜덤포레스트(GVsearch, RandomizedSearch), 그래디언트 부스팅
* 제공 데이터 : 2017년 4월 1일 ~ 5월 31일 시간별 서울시 따릉이 대여수와 기상상황 
 >(1) train.csv : 서울시 마포구의 날짜별, 시간별 기상상황과 따릉이 대여 수 (기간: 2017년 4월, 5월) 
 
 >(2) test.csv : count 외에는 train 데이터와 동일 
 
 >(3) submission.csv : submission 파일의 예시
* * * 
* 최종 제출 : 2021-09-07
* 리더보드 순위 : 23/557 (2021-12-08 기준)

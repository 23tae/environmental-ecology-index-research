# 서울시 자치구별 환경생태지수 평가

## 연구 과정

1. 녹색도시지수(GCI)를 바탕으로 환경생태지수 정의
2. 평가 항목에 따라 데이터 수집
3. 서울시 자치구별 환경생태지수 평가

## 평가 항목

- 온실가스 배출량
- 전력 사용량
- 대기질
- 공공자전거 이용량
- 물 사용량
- 쓰레기 배출량

## 연구 내용

### 데이터 수집

![data](/assets/seoul_ecological_data.png)

### 데이터 정규화

![normalized_data](/assets/seoul_ecological_data(normalized).png)

## 연구 결과

![seoul_ecology_index_map](/assets/seoul_ecology_index_result.png)


## 활용 데이터

- 온실가스 배출량 통계 (서울특별시)
- 서울특별시 전력 사용량 (용도별) 통계 (서울특별시)
- 서울특별시 공공자전거 대여소별 월별 이용정보 (서울특별시)
- 서울시 상수도 급수 사용량 및 사용료 통계 (서울특별시)
- 서울시 주민 1인당 생활폐기물 (쓰레기) 배출량 통계 (서울특별시)
- 서울시 대기오염 (구별) 통계 (서울특별시)
- 서울시 공원 통계 (서울특별시)

## 파일별 분석 내용

- `ghg_emission_analysis.ipynb`: 온실가스 배출량
- `electricity_consumption_analysis.ipynb`: 전력 사용량
- `air_pollution_analysis.ipynb`: 대기질
- `bicycle_analysis.ipynb`: 공공자전거 이용량
- `water_consumption_analysis.ipynb`: 물 사용량
- `waste_emission_analysis.ipynb`: 쓰레기 배출량
- `population_analysis.ipynb`: 인구
- `park_area.ipynb`: 공원 면적
- `environmental_index_analysis.ipynb`: 데이터 분석
- `draw_index.ipynb`: 환경생태지수 산출
- `map_visualize.ipynb`: 지도 시각화
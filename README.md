# 공모전 진행
작업 기간 : 2022.09 ~ 2022.10
프로젝트 목적 
- 코로나 19로 인해 배달요리 증가로 인해 일회용품 쓰레기 발생이 큰 문제가 되었고, 일회용품과 쓰레기 문제를 해결하기 위해 다회용기를 통한 해결 문제가 각광 받게 되었다.
- 다회용기를 사용하기 위한 다회용기 세척센터를 건설하고자 세종시 내에 다회용기 세척센터를 세우기 위한 가장 최적의 곳(공시지가, 음식물 처리량 등)을 분석하고 최적의 위치를 제시함
주요 업무
- 데이터 전처리 : 세종시 인구를 시군구 별로 나누는 작업 진행,  QGIS를 활용한 shp파일을 geojson으로 변환
- 시각화 : Folium 모델과 클러스터링 모델을 활용해 세종시의 현황 표현
- 머신러닝 : RandomForest를 활용해 거주 인구수, 월평균 배달수, 음식점 개수, 음식물 쓰레기 배출량 4개의 변수를 표준화, K-means와 가우시안 모델을 활용해 cluster의 행정동 기준 변수의 평균 합을 기준으로 순위가 가장 높은 Cluster 확인
사용 언어 : Python, Excel, QGIS(지도 시각화)
느낀 점 : 일회용기로 인한 쓰레기 문제가 심각한 것을 알게 되었으며, 최적의 입지선정에 대한 기준을 알게 되었음
참고자료 
- 주민등록통계인구 : https://jumin.mois.go.kr/
- 용기내 세종 등 : https://www.sejong.go.kr/kor/sub04_041401.do;jsessionid=564992017CB507010BD672C492523CF6.portal2

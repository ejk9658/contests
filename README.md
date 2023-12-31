## [강원도 소방본부 구급 출동 AI 예측](https://ejk9658.notion.site/AI-4b241e651a0340e0b5f386beab5a0c4d?pvs=4)

2021.11.30 ~ 2021.12.17

✔️**주제**

강원도의 2020년 매월 마지막 날의 시간대별 구급출동이 발생한 격자를 예측합니다.

✔️**목표**

강원도는 넓은 산악 지형으로 이루어져 있고, 구급 인력이 부족하여 골든 타임을 쉽게 놓칩니다.
구급 수요 예측을 위하여 강원도 소방본부 **구급출동 데이터 및 관련 데이터를 학습하여 AI 예측 모델을 구축합니다.
이후에 2020년 매월 마지막 날의 시간대별 구급출동이 발생한 격자를 예측합니다.

** 구급출동 데이터 설명 : <br>
강원도 지역을 그리드로 나눈 후, 격자별로 매 시각(hour)의 구급출동 건수 데이터. <br>
2020년 1월 00시부터 2020년 12월 31일 23시 중에 매월 말 데이터가 빠져 있다. <br>
즉, 366일*24시간 중 12일*24시간을 뺀 데이터가 들어있다. <br>
해당 데이터를 이용하여 빠진 데이터를 예측하는 것이 대회의 목표이다.

✔️**결과**

[소스코드](/%EA%B0%95%EC%9B%90%EB%8F%84%20%EC%86%8C%EB%B0%A9%EB%B3%B8%EB%B6%80%20%EA%B5%AC%EA%B8%89%20%EC%B6%9C%EB%8F%99%20AI%20%EC%98%88%EC%B8%A1_%EC%9D%BC%EC%84%9D%EC%82%BC%EC%A1%B0%ED%8C%80_%EB%8C%80%EC%83%81.ipynb)

✔️**프로젝트 성과**

31.6%에 달하는 높은 예측률을 보이며 대상을 수상함.

![image](https://github.com/ejk9658/contests/assets/55371726/390f4b23-75c3-40b3-8895-ca34a0e1795f)

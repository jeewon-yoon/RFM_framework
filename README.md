## 대형마트 고객 세분화 분석
**프로젝트 상세 소개:** [포트폴리오 링크](https://drive.google.com/file/d/1NPSMdHk9HeCqIAqaSs0D2LexnZ8GOmPE/view?usp=drive_link)  <br>   

2년동안 마트에 가입한 고객 데이터를 RFM 분석 프레임워크를 적용하여 분석 후 마케팅 전략 제안.      
<br>

> ### 배경 및 현황
- 이커머스 기업들의 급성장으로 오프라인 매장의 실적 감소, 이를 극복하기 위해 오프라인 매장들은 다양한 마케팅 전략을 시도하고 있음.
- 축적된 고객 데이터를 분석하여 마트의 마케팅 전략에 활용하고자 함.    

   
> ## 데이터셋  
- 2년동안 마트에 가입한 고객들의 정보
  - ID
  - 출생연도
  - 자녀 수
  - 결혼상태
  - 품목별 소비액
  - 마지막으로 방문한 날부터 현재까지 경과일 수
  - 온라인몰•할인행사•매장에서 구매한 횟수
  - 프로모션 1~5 참여횟수      


> ## 지표 선정
+ Recency: 마지막으로 방문한 날부터 현재까지 경과일 수
+ Frequency: 온라인몰 • 할인행사 • 매장에서 구매한 횟수
+ Monetary: 품목별(육류, 과자, 일반, 주류, 과일, 생선) 소비액

<p align="center"><img src="https://github.com/user-attachments/assets/5f03bd07-b6c5-4dd5-b249-d67f444ff426" width="273" height="200" data-align="center"></p>

> ## 분석 방법론  
- Python(pandas, matplotlib, seaborn, sklearn)을 이용하여 고객수를 기준으로 3분위 구간 나누기를 진행. RFM 지표별 고객 등급별로 소비액을 pieplot으로 나타냄. 3 지표의 매출기여도를 고려하여 가중치 조정.
- K-means 군집화 분석을 통해 최적의 군집 개수를 파악.    


## 인사이트  
- K-means 군집화 분석을 통해 우수고객의 특성을 더 명확하게 파악가능. 돈을 많이 쓰는 고객일수록 평소 마트 행사에 많이 참여함       

   
## 액션
마케팅 팀에게 분석결과를 전달!
- 생필품보다 주류, 육류 상품군에 더 집중하여 물품을 구비
- 우수고객이 프로모션 5에 긍정적으로 반응한 이유를 분석
- 전반적으로 참가율이 높았던 프로모션 6의 내용을 분석   




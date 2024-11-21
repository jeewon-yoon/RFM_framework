### <대형마트 고객 세분화 분석>

#### 프로젝트 소개

매출액 성장률 하락을 막기 위해 기존 고객을 대상으로 마케팅을 기획하고 있는 마케팅 팀에게 2년동안 마트에 가입한 고객 정보 데이터 분석결과를 전달.   

**데이터셋** 
2년동안 마트에 가입한 고객의 인구통계학적 정보, 품목별 소비액, 마지막으로 방문한 날부터 현재까지 경과일 수, 온라인몰•할인행사• 매장에서 구매한 횟수, 프로모션 1~5 참여횟수

**지표 선정**

Recency

Frequency

Monetary 
<img src="file:///C:/Users/elley/git_vscode/jeewon-yoon.github.io/assets/798d2ac6f40b27ccadea575ed01da6c1e466d1e3.png" title="" alt="logl" width="204">

**분석 방법론**  
Python(pandas, matplotlib, seaborn, sklearn)을 이용하여 고객수를 기준으로 3분위 구간 나누기와 k-means 군집화 분석을 진행. 시각화(pieplot, barchart)를 진행. 

**액션** 
생필품보다 주류, 육류 상품군에 더 집중하여 물품을 구비

우수고객이 프로모션 5에 긍정적으로 반응한 이유를 분석

전반적으로 참가율이 높았던 프로모션 6의 내용을 분석

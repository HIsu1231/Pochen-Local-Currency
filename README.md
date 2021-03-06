# Pochen-Local-Currency
[NIA] 포천시 지역화폐 소비패턴 분석 및 활성화

## 1. 활용데이터
<table>
  <tr>
    <td>구분</td><td>분석데이터</td><td>기간</td><td>제공기관</td>
  </tr>
  <tr>
    <td>지역화폐 충전정보</td><td>포천_charge20190429.csv ~ 포천_charge20210726.csv</td><td>2019.04.1~ 2021.07.31</td><td>포천시청</td>
  </tr>
  <tr>
    <td>가맹점 위치</td><td>경기지역화폐_가맹점리스트_1007_포천.csv</td><td>2021.08.31</td><td>포천시청</td>
  </tr>
  <tr>
    <td>포천시 주거별 세대 수 데이터</td><td>인구_가구_및_주택_읍면동_2015_2020_시군구.csv</td><td>2020</td><td>통계청</td>
  </tr>
 </table>
 
## 2. 사전 EDA
   #### 사용자 수 기준 성별 비교
   <img src="https://user-images.githubusercontent.com/54710010/169965619-18ce560c-e686-45cc-b2bc-7203232203e2.png" width="300" height="250"/>
   
   #### 사용자 수 기준 연령대 비교
   <img src="https://user-images.githubusercontent.com/54710010/169965724-9213136e-96d8-45cc-9076-8bfdc4652a2d.png" width="300" height="250"/>

  
   #### 일반 발행, 일반 정책 발행, 긴급 정책 발행(코로나) 연령대별 발행 건수 비교
   <div>
   <img src="https://user-images.githubusercontent.com/54710010/169965768-5f0cae8d-54e4-4011-b372-7cea66492779.png" width="300" height="200"/>
  <span>&nbsp</span>
   <img src="https://user-images.githubusercontent.com/54710010/169965795-0fc8ecce-f52a-491a-8dbf-fc299fe86625.png" width="300" height="200"/>
  <span>&nbsp</span>
   <img src="https://user-images.githubusercontent.com/54710010/169965804-4552cf4d-9d34-4832-9f78-db5f5922a364.png" width="300" height="200"/>
  </div>
 
   #### 포천시 행정구역별 결제 견수와 결제 금액 비교
  <div>
   <img src="https://user-images.githubusercontent.com/54710010/169968522-3421accc-71c6-4fe4-a290-21cbcf3eb90b.png" width="400" height="250"/>
  <span>&nbsp</span>
   <img src="https://user-images.githubusercontent.com/54710010/169968566-699fd56e-f141-47e6-b088-d03781c410df.png" width="400" height="250"/>
  </div>
   
   #### 지역화폐 소비 업종 상위 10개
  <div>
   <img src="https://user-images.githubusercontent.com/54710010/169968888-14e8f62c-936e-46e5-804c-1e7d1b962533.png" width="350" height="250"/>
  <span>&nbsp</span>
   <img src="https://user-images.githubusercontent.com/54710010/169968969-0e4d3bf7-3cf4-448d-92de-1385b32e46f5.png" width="350" height="250"/>
  </div>
  
  ### 포천시 지역화폐 발행 현황
  #### 결제 건수 기준 정책 발행 상위 10개
  <img src="https://user-images.githubusercontent.com/54710010/169969522-395ed6f6-45aa-4d5a-b07c-1b6eaadbd8c0.png" width="350" height="250"/>
  
  #### 결제 금액 기준 정책 발행 상위 10개
  <img src="https://user-images.githubusercontent.com/54710010/169969644-ea2a63eb-615b-4a8c-97fd-87222e344645.png" width="350" height="250"/>
  
  ### 포천시 행정구역별 가맹점 현황
  
  #### 행정구역별 가맹점 수
  <div>
  <img src="https://user-images.githubusercontent.com/54710010/169969929-72946607-2ae6-4db6-9c13-8ee869b55eeb.png" width="350" height="250"/>
  <span>&sbsp</span>
  <img src="https://user-images.githubusercontent.com/54710010/169970055-15a883bf-d339-447b-9321-c506f64f4c0d.png" width="350" height="250"/>
  </div>
  
 #### 총 소비금액 기준 상위 10개 업종 연령대/성별 비교
  <img src="https://user-images.githubusercontent.com/54710010/169970804-24efebe2-1c7a-429a-8534-8f786a3d1fef.png" width="450" height="350"/>
  
 ## 3. 노년층의 지역화폐 사용 활성화 방안
 ### 3.1 배경
 <br> 지역 화폐의 연령대별 발행명과 사용 패턴을 분석하였을 때, 성인 인구 기준 60세 이상부터 사용 인원 및 금액이 현저하게 줄어드는 것을 발견하였다. 이 외에 발행 성격에 따라 일반 발행, 일반 정책 발행, 코로나 정책 발행으로 분류하여 연령대별 발행 비율을 살펴보았을 때, 60대 이후로 세 가지 항목 모두 발행 건수가 60대 이전 연령대에 비해 적었고, 일반 정책 발행 비율이 거의 없었다. 따라서 노인 인구(60대 이상)와 비노인(60대 미만) 인구의 지역화폐 사용 비교를 통해 인사이트를 도출하려 한다. </br>
 
 ### 3.2 지역별/연령대별 사용자 비교
 #### 행정구역별 60세 이상 지역화폐사용자비
 <table>
  <tr>
    <td></td> <td>60세이상지역화폐사용자비</td>
  </tr>
  <tr>
    <td>창수면</td><td>0.303039353</td>
  </tr>
    <tr>
    <td>영중면</td><td>0.28303332</td>
  </tr>
  <tr>
    <td>관인면</td><td>0.296006478</td>
  </tr>
  <tr>
    <td>내촌면</td><td>0.345601157</td>
  </tr>
  <tr>
    <td>일동면</td><td>0.417083791</td>
  </tr>
  <tr>
    <td>영북면</td><td>0.303039353</td>
  </tr>
  <tr>
    <td>가산면</td><td>0.449662342</td>
  </tr>
  <tr>
    <td>화현면</td><td>0.325812784</td>
  </tr>
  <tr>
    <td>이동면</td><td>0.39755105</td>
  </tr>
  <tr>
    <td>포천동</td><td>0.438337002</td>
  </tr>
  <tr>
    <td>신북면</td><td>0.358913435</td>
  </tr>
  <tr>
    <td>선단동</td><td>0.439275982</td>
  </tr>
  <tr>
    <td>군내면</td><td>0.320208243</td>
  </tr>
   <tr>
    <td>소흘읍</td><td>0.47024587</td>
  </tr>
   </table>
   
## 4. 결론 및 한계점
### 4.1 요약
- 지역화폐 총 소비 금액, 건수 기준 가장 많은 소비를 한 업종은 각각 일반한식(19%), 편의점(21%)이다. 이 외에 소비 업종 상위 10개 과반 이상이 식품과 관련된 업종이다.
-	소비가 가장 많은 지역은 포천시 소흘읍으로 약 180억이 소비되었으며, 그 다음으로는 포천동이 약 8억원 가량 소비하였다. 소비 금액 비율을 보았을 때, 소흘읍과 포천동 두 지역이 전체 소비의 과반 이상(52.9%)를 차지한다. 
- 노인 인구의 지역화폐 사용률이 저조함에도 지역에 따라 그 비율에 차이가 있다.


### 4.2 정책 제언
- 노인을 대상으로 하는 정책 지원을 늘려 지역 화폐 사용률을 높인다. 
- 	한국지능정보사회진흥원(NIA)의 ‘디지털 포용본부’와 같이 연령 간 디지털 격차를 줄이기 위하여 노인 인구 밀집 지역을 우선으로 활발한 홍보 및 교육을 실시한다.
- 	외식업과 슈퍼마켓과 같이 식품과 관련한 업종을 소비할 때 추가적인 인센티브를 제공한다면 지역화폐 사용자를 늘리고 지속적인 사용을 기대할 수 있다.



  
 
 

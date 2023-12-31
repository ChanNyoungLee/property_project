<h2 align="center"> 
  <br> 
  부동산 데이터 분석 프로젝트
</h2>

<h3 align="center">
</h3>  
<p align="right">
  <br>
  프로젝트 기반 빅데이터 서비스 개발자 양성 과정 4기  
  <br>⠂이찬녕</br>
</p>  


### Abstract
한국자산관리공사_국유부동산 매각현황_20211231 데이터를 이용해서 14년부터 22년까지의 매각 현황을 분석하고, 인사이트를 얻어서 앞으로의 매각 추세를 파악하기 위해 프로젝트를 	실시하였습니다.

### Method
데이터 분석을 위해 결측치 유무를 확인해보니 총 141312개의 데이터 중에서 85개의 결측치가 있는 것이 확인되었고, 총 데이터의 수에 비하여 결측치의 수가 적다고 판단되어서 결측치가 있는 관측값을 제거한 141,231개의 데이터로 분석을 실시하였습니다.

### Result
 매각 금액이 가장 많은 팀과 하위 팀의 차이를 확인하기 위해서 우선, 데이터에 ‘팀명’이라는 	변수로 들어가 있는 매각을 진행한 팀의 이름의 종류를 조회해 본 결과, 총 66개의 팀에 의해	매각이 진행된 것을 확인했습니다. 각 팀 별로 매각한 부동산의 대장금액의 합계를 구한 뒤, 합계가 	가장 큰 팀과 가장 작은 팀의 차이를 구했습니다.
              대장금액의 합계가 가장 큰 팀은 국유재산3팀 이었으며, 대장금액은 1,581,917,203,990	원이었습니다. 대장금액의 합계가 가장 작은 팀은 해안면무주지국유화지원추진단 이었으며,
	대장금액은 22,101,960원으로 두 팀의 대장금액 합계의 차이는 1,581,895,102,030원 	이었습니다.
 
<p align="center">
  <img src="https://github.com/ChanNyoungLee/-/blob/master/%EC%9D%B4%EB%AF%B8%EC%A7%80/%EC%9D%B4%EB%AF%B8%EC%A7%801.png" width="400"/>
</p>
<br>

▪ 매각면적 상위 5개의 지역별 매각 면적을 확인하기 위해서 제곱미터 단위로 된 대장면적	 	데이터의 합계를 각 지역별로 구하였습니다. 지역별 대장면적 합계 값의 순위는 강원도가
	13,355,279.95m2로 1위를 했으며, 경기도가 11,199,309.48m2로 2위, 전라남도가 	9,388,420.737m2로 3위이고, 경상북도가 7,053,822.672m2로 4위, 그리고 마지막으로
	충청남도가 8,580,609.586m2로 5위를 했습니다.

▪ 계약일자를 기준으로 매각이 많은 때의 특징을 알아보기 위해서 계약일자 별로 갯수를  	파악했습니다. 총 141231개의 데이터 중에서 계약일자는 2784종류였으며, 갯수가 많은 상위 1%	인 27개의 계약일자를 찾았습니다. YYYY-MM-DD 형식으로 되어있는 계약일자 중에서 DD 	부분만 	보았습니다. 1일, 30일, 25일, 01일, 29일, 27일, 26일, 21일, 10일, 01일, 20일,
	11일, 21일, 21일, 26일, 07일, 30일, 31일, 13일, 22일, 22일, 27일, 31일, 16일, 31일, 30일,
	28일로 나와서 주로 월초나 월말에 계약되었다고 추측했습니다.

▪  부동산을 처분하는 방법들의 비율을 분석하기 위해서 처분 구분명으로 되어있는 변수를 종류별로
	파악했습니다. 총 8가지의 처분 방법이 있었으며, 그 중에서 매각수의가 약 88.17%로 가장 	많았으며, 유상양여가 전체에서 1건인 약 0.0007%로 가장 적었습니다. 다른 방법들로는 	무상관리전환이 약 3.04%. 매각입찰이 약 6.25%, 유상관리전환이 약 0.08%, 무상양여가 약 	0.49%, 사용승인이 약 1.48%, 그리고 마지막으로 무상귀속이 0.5%로 나왔습니다.

 <p align="center">
  <img src="https://github.com/ChanNyoungLee/-/blob/master/%EC%9D%B4%EB%AF%B8%EC%A7%80/%EC%9D%B4%EB%AF%B8%EC%A7%802.png" width="400"/>
</p>
<br>

▪ 3번째 분석이었던 지역별 매각면적의 상위 5개를 지역 규모에 따라서 비교해보았습니다. 각 도, 	광역시, 특별시, 특별자치시, 특별자치도의 면적을 지역별 매각면적의 합계로 나누어서 상위 5개의
	순위를 비교했을 때는, 강원도가 강원도 면적의 약 1.3%를 매각해서 1위, 충청남도가 약 0.94%로 	2위. 전라북도가 약 0.76%로 3위, 충청북도가 약 0.7%로 4위, 전라남도가 약 0.55%로 5위를 	했습니다.

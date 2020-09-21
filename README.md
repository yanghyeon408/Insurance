# Insurance 사기자 판별 프로젝트

## 프로젝트에 사용 할 파일
고객 데이터: CUST_DATA.csv
보험 청구 데이터: CLAIM_DATA.csv

## 요구사항
소스코드: 홍길동.ipnb. 
소스코드는 Run All 했을 경우 데이터를 학습한 후 아래의 csv 파일이 자동으로 만들어져야 합니다. 
보험사기를 분류한 결과 csv 파일: 홍길동_결과.csv. 
이 파일은 보험 사기자를 예측해야 하는 사람들의 아이디가 있습니다. 데이터를 분석한 후 이 사람들이 사기자이면 1, 그렇지 않으면 0을 표시해서 csv 파일(쉼표분리)로 만들어 제출해야 합니다. 

## 평가방법
평가는 f-meaure(precision 과 recall의 조화편균)를 이용합니다.

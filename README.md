## 논문
### [분류 모델링과 클러스터링 결합 방법을 통한 주가 시계열 데이터에서의 상승 추세 패턴 검출 기법](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11224523) 
주가 빅데이터는 수 년 동안 수 천 개 종목의 가격 변화를 기록한 패널 시계열 데이터로, 시계열 분야에서  연구적으로  중요한  가치를  가지는  빅데이터이다.  본  연구에서는  일  단위  주가  데이터에서  다음  날 종가의 상승 여부를 예측하는 분류 모델을 만들고, 이 분류 모델을 사용하여 SHAP 데이터 표준화를 실시하고,  클러스터링하여  주가  상승  종목이  높은  비율로  포함된  상승  패턴형  군집을  선택함으로  상승  추세 패턴을  검출하는  방법론을  제안한다.  한국증권시장(KOSPI,  KOSDAQ)의  종목들에  적용하였을  때,  검출한 상승  패턴  군집의  종목들의  공통된  패턴은  V자  반등형  추세  전환  패턴이었으며,  일주일  정도의  짧은  기간에 여러  종목이  몰려서  검출되었다.  이를  통해,  여러  종목이  하락  후  상승할  때,  시장  전체가  상승하는  상승 초입  시그널이라는  해석을  할  수  있었다.   

#### **주가 상승 추세 패턴 검출 방법론 도식화 그림** 
![image](https://github.com/ag-su/stock_prediction_research/assets/72302404/77b80b45-b0ac-4af3-8586-8eaf25759f0b)


<br>
<br>

## 연구
### 1. 베이스라인 모델 선택 
#### [01.stock_dataset.ipynb](https://github.com/ag-su/stock_prediction_research/blob/main/01.stock_dataset.ipynb)


#### [02.model_selection.ipynb](https://github.com/ag-su/stock_prediction_research/blob/main/02.model_selection.ipynb)


### 2. 데이터 전처리 
#### [03.add_index.ipynb](https://github.com/ag-su/stock_prediction_research/blob/main/03.add_index.ipynb)


#### [04.scaling.ipynb](https://github.com/ag-su/stock_prediction_research/blob/main/04.scaling.ipynb)


#### [05.filtering.ipynb](https://github.com/ag-su/stock_prediction_research/blob/main/05.filtering.ipynb)


### 3. 주가 상승 추세 패턴 검출 연구
#### [06.shap_value.ipynb](https://github.com/ag-su/stock_prediction_research/blob/main/06.shap_value.ipynb)


#### [07.tsne.ipynb](https://github.com/ag-su/stock_prediction_research/blob/main/07.tsne.ipynb)


#### [08.cluster_filtering.ipynb](https://github.com/ag-su/stock_prediction_research/blob/main/08.cluster_filtering.ipynb)


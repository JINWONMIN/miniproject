## Ex.11 주가 예측
* * *
* **실습 목표**
  * 시계열 데이터의 특성과 안정적(Stationary) 시계열의 개념을 이해
  * ARIMA 모델을 구성하는 AR, MA, Diffencing의 개념을 이해하고 간단한 시계열 데이터에 적용
  * 실제 주식 데이터에 ARIMA를 적용해서 예측 정확도를 확인

<br/>

* **Rubric**

|**평가항목**|**평가기준**|
|:---:|:---:|
| 시계열의 안정성이 충분히 확인되었는지|플로팅과 adfuller 메소드가 모두 적절히 사용되었음|
| ARIMA 모델 모수선택 근거를 체계적으로 제시하였는지|p,q를 위한 ACF, PACF 사용과 d를 위한 차분 과정이 명확히 제시됨|
| 예측 모델의 오차율이 기준 이하로 정확하게 나왔는지|3개 이상 종목이 MAPE 15% 미만의 정확도로 예측됨|
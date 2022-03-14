## Ex.06 다음에 볼 영화 예측하기(Session Based Recommendation)
* * *
* **실습 목표**
  * 사용할 모델은 2016년 ICLR에 공개된 [SESSION-BASED RECOMMENDATIONS WITH RECURRENT NEURAL NETWORKS](https://arxiv.org/pdf/1511.06939v4.pdf)
  * 해당 논문은 Session Data에서는 처음으로 RNN 계열 모델을 적용하여 발표한 논문이다.
  * 논문의 내용은 추가적으로 정리해서 업로드 할 예정이다.


<br/>

* **Rubric**

|**평가항목**|**평가기준**|
|:---:|:---:|
|Movielens 데이터셋을 session based recommendation 관점으로 전처리하는 과정이 체계적으로 진행되었는지|데이터셋의 면밀한 분석을 토대로 세션단위 정의 과정(길이분석, 시간분석)을 합리적으로 수행한 과정이 기술되었다.|
| RNN 기반의 예측 모델이 정상적으로 구성되어 안정적으로 훈련이 진행되었는지|적절한 epoch만큼의 학습이 진행되는 과정에서 train loss가 안정적으로 감소하고, validation 단계에서의 Recall, MRR이 개선되는 것이 확인된다.|
|세션정의, 모델구조, 하이퍼파라미터 등을 변경해서 실험하여 Recall, MRR 등의 변화추이를 관찰하였다.|3가지 이상의 변화를 시도하고 그 실험결과를 체계적으로 분석하였다.|

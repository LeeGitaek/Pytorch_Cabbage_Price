# Pytorch_Cabbage_Price
Pytorch, Python 을 사용한 배추가격예측

## 모델 학습 <br>
**[1] H(x) = Wx+b  함수로 가설을 설정하였습니다.**  <br>
 > 평균온도 x1 , 최저온도 x2 , 최대온량 x3 , 강우량 x4<br>
  weight 는 w1,w2,w3,w4 <br>
  따라서 Hypothesis = x1 * w1 + x2 * w2 + x3 * w3 + x4 * w4 + b 라는 가설함수를 도출하게 됩니다.<br>
     <br>
     <br>
    
**[2] 비용 함수 ( Cost Function ) 또는 Loss Function** <br>
    > cost function = 1/2 𝑚∑𝑖=1𝑚(ℎ(𝑥(𝑖)−𝑦(𝑖))^2 로 설정하였습니다. <br>
    <br>
    <br>
**[3] cost 비용을 최소화 하기 위한 최적화 알고리즘 / 경사하강법** <br>
    > learning _ rate = 0.000005 로 설정하였으며,<br>
    > epoch = 100001 만큼 학습하였습니다.<br>
    <br>
    <br>
**[4] 데이터 예측**<br>
    > #평균 온도 최저 온도 최고 온도 강수량 : -2.7 / : -6.6 / : 2.0 / : 0.1<br>
    > 가격 예측 결과  : 2000.4521 <br>
    

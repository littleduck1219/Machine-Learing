# Machine-Learing
“데이터를 구문 분석하고 해당 데이터를 통해 학습한 후 정보를 바탕으로 결정을 내리기 위해 학습한 내용을 적용하는 알고리즘”

## Supervised Learning : 지도학습
훈련 데이터가 주어지고 훈련 데이터로 부터 값을 유추해내기 위한 학습입니다.

### <li>Classification(분류)
분류할 대상이 정해져있는 상태로, 개와 고양이처럼 Label로 개와 고양이의 데이터를 다량으로 입력하여 분류해주면 컴퓨터가 특징을 분석 파악하여 새로운 개 고양이 사진을 줬을 때 판단하여 분류 하는 것입니다.</li>

### <li>Regression(회귀)
키에 따른 신발 사이즈, 시간에 따른 커피 소비량과 같이 상관 관계가 있는 데이터를 수집하여 그래프에 점을 찍어 그리면 데이터의 분포가 생긴다 그 분포를 가로지르는 평균선이 나타나게 됩니다. 그 평균선을 기준으로 새로운 데이터를 입력하였을때, 예측(predict)을 하게 됩니다. 예측이기 때문에 오차가 존재하고 그 오차를 error라고 부르고 줄여나가는 것을 목표로 데이터를 다루게 됩니다.</li>

## Unsupervised Learning : 비지도학습
문제만 제공하여 문제안에서 패턴을 찾아냅니다. 일반적으로 지도학습보다 정확도가 떨어집니다.\
문제만제공 : Feature\
패턴/구조 발견 : 구룹화(Anomaly, Clustering)\

### <li>Anomaly(변칙검색)
예를들어 카드사의 결제 시스템처럼, 금융사기를 막기위해 평소 쓰던 결제 패턴에서 갑자기 증가한패턴을 발견하게된다면, 결제가 정지된다던지 큰 결제가 들어왔다고 알림이 오는 서비스처럼 평상시 패턴을 조합하고 있다가 다른 패턴이 발견되면 알리는 것입니다. 항공기, 선박에서의 평상시 패턴을 학습하고 있다가 다른 패턴이 발생하면 알려 수리시기를 알려준다.</li>

### <li>Clustering(군집)
분류되지않은 다량의 데이터가 있을때 알고리즘으로 각각의 군집으로 구분화 시켜주고 라벨링을 해줌으로써 데이터를 학습한다. 당연히 지도학습에 비해 정확도는 많이 떨어진다. 라벨링이 되어있지만 신뢰도가 떨어질때 사용한다.</li>


## Reinforcement Learning : 강화 학습


# Deep Learning
딥 러닝 모델은 인간이 결론을 내리는 방식과 유사한 논리 구조를 사용하여 데이터를 지속적으로 분석하도록 설계되었습니다. 이를 달성하기 위해 딥 러닝 애플리케이션은 인공 신경망이라는 계층화된 알고리즘 구조를 사용합니다. 인공 신경망의 설계는 인간 두뇌의 생물학적 신경망에서 영감을 얻어, 표준 머신 러닝 모델보다 훨씬 더 뛰어난 학습 프로세스를 제공합니다.

# Data

1단계 : Understand the Business Domain 해당되는 영역에 대한 이해\
2단계 : Understand the Business Problem 해당되는 영역에 진짜 문제\
3단계 : What is the Right Data, Right Column and Right Algorithm 정확한 데이터, 컬럼, 알고리즘을 준비\
4단계 : Knowledge With Machine Learning

label : 실제로 알고싶은 데이터
feature : label에 영향을 미치는 데이터
불필요한 feature는 직접 제외시켜줘야 합니다.
<img src="https://user-images.githubusercontent.com/107936957/201516852-a86f9eca-ce28-47de-9ea2-191b54c5079d.png">
(https://zinayouhan33.medium.com/machine-learning-can-be-divided-into-3-categorizations-supervised-unsupervised-and-reinforcement-9a1b47460f5d)

평가를 위해서 데이터를 쪼개서 사용합니다.
X_train, y_train : 학습용set
X_test, y_test : 검증용set

단순히 데이터가 정렬된 상태에서 학습이나 테스트를 실시하게되면 편향된 결과가 발생하기 때문에 내용을 충분히 섞어서 실시합니다..
섞을때도 선택이 좋았던 건지 확실할 수 없기에 seed값을 줘서 횟수를 지정합니다.

![1_rBx2D83rNUloJsq5gC_QIw](https://user-images.githubusercontent.com/107936957/201516991-177d29a8-ef8a-4f4d-90b0-f7d9af8d8551.png)
(https://www.kdnuggets.com/2021/01/ultimate-scikit-learn-machine-learning-cheatsheet.html)

------------------------------------------------------------------------------------------------------------------------
# Orange
데이터처리 및 시각화 그리고 머신 러닝을 직접적으로 적용해 볼 수 이쓴 도구.



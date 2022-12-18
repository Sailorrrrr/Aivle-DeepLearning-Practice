# Aivle-DeepLearning-Practice
AivleSchool 2기 딥러닝 실습

* 딥러닝을 위한 데이터 전처리
  1. X,y 구분 -> 스케일링 -> train, val 나누기 (데이터가 많을때는 상관없다. 데이터 적으면 학습이 제대로 안될 수 있다.)
  2. X,y 구분 -> train, val 나누기 -> train을 기준으로 스케일링 후 Val 데이터는 적용만 (교과서적인 방법)

  학습을 위해 train set을 0~1로 맞추는 것이 스케일링의 목적임. 딥러닝에서는 스케일링 필수적. 

* 딥러닝 코드 구조 익히기 
  - 모델 설계 -> 컴파일(어떻게 학습시킬것인가 결정) -> 학습 -> 학습그래프 확인 -> 검증
  
  - 모델설계시 히든레이어의 의미 
    Output layer를 제외한 레이어들은 모두 히든레이어임.
    히든레이어들은 반드시 activation 함수를 통해 다음 노드로 값을 전달한다.
    예를들어 relu 활성화 함수를 사용한다면, 0보다 큰 값은 다음 노드로 넘겨지는것. 


* Regression 코드 이해 
  
![image](https://user-images.githubusercontent.com/97539668/208284113-59c67453-32dd-47d8-9e07-76d0404c92f4.png)
![image](https://user-images.githubusercontent.com/9753Epochs = 10

  Epochs = 10
    - epochs : 500건 전체를 10번 학습
  Batch_size = 100
    - Batch 하나당 데이터 건수
    - 전체 / batch_size  5개의 batch로 나눠서 학습
  iteration 수 (update 수)
    - epochs = 10, batch_size = 100 라면
    - 10 * (500/100) = 50 회 반복하며 파라미터 업데이트
  validation_split 
    - 학습 시 일부를 나눠서 검증용으로 사용




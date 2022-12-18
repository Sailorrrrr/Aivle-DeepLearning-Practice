# Aivle-DeepLearning-Practice
AivleSchool 2기 딥러닝 실습

* 딥러닝을 위한 데이터 전처리
  1. X,y 구분 -> 스케일링 -> train, val 나누기 (데이터가 많을때는 상관없다. 데이터 적으면 학습이 제대로 안될 수 있다.)
  2. X,y 구분 -> train, val 나누기 -> train을 기준으로 스케일링 후 Val 데이터는 적용만 (교과서적인 방법)

  학습을 위해 train set을 0~1로 맞추는 것이 스케일링의 목적임. 딥러닝에서는 스케일링 필수적. 

* 딥러닝 코드 구조 익히기 
  모델 설계 -> 컴파일(어떻게 학습시킬것인가 결정) -> 학습 -> 학습그래프 확인 -> 검증

* Regression 코드 이해 
  
  
![image](https://user-images.githubusercontent.com/97539668/208284113-59c67453-32dd-47d8-9e07-76d0404c92f4.png)
![image](https://user-images.githubusercontent.com/97539668/208284131-cb1ac760-4ad2-4b5d-b2dd-fad3d2437abc.png)

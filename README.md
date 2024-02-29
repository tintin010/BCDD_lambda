## Lambda 함수 생성 방법
LambdaFunction을 통해 함수를 생성할 때 init 내부의 파일도 같이 넘겨주어야 한다.

#### 람다 함수는 API Gateway를 이용하여 외부와 통신을 하게 된다.

함수들은 LambdaFunction 폴더 아래에 있고 이들은 각 함수에 하나씩 넣어서 함수를 구성하면 됨.

### <함수 구성 형태>
![image](https://github.com/tintin010/BCDD_lambda/assets/82323029/e95065f9-0468-42ee-8935-7fc39722f07f)

### <함수와 연결되어 있는 게이트웨이>
메소드별로 게이트웨이를 지정해주면 된다.
![image](https://github.com/tintin010/BCDD_lambda/assets/82323029/56569513-f27a-40b5-a036-079c6fd53ab6)

### 게이트웨이 설정은 해당 페이지에서 하면 된다.
![image](https://github.com/tintin010/BCDD_lambda/assets/82323029/a71e0c9b-10ac-4224-8774-3d6aa3a0d0e3)


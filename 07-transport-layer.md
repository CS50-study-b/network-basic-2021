# 4계층 프로토콜

## 4계층에서 하는 일
- 전송계층은 송신자의 프로세스와 수신자의 프로세스(메모리에서 동작중인 프로그램)를 연결하는 통신 서비스 제공

## 4계층 프로토콜의 종류

![07-udp](https://user-images.githubusercontent.com/51018201/127729655-b1531320-1460-4f75-a7ee-b762e62ebb9a.jpg)

UDP 프로토콜 – 비연결형 프로토콜(장비간 연결을 맺지 않고 데이터 전송)

![07-tcp](https://user-images.githubusercontent.com/51018201/127729654-f417d077-2e9e-4c75-ac78-e9badac40867.jpg)

TCP 프로토콜 – 연결형 프로토콜(연결이 된 이후에 전송)

# 포트 번호

## 포트 번호의 특징
- 특정 프로세스와 특정 프로세스가 통신하기 위해 사용
- 하나의 포트는 하나의 프로세스만 사용 가능
- 상대방 컴퓨터의 여러 개의 프로세스는 하나의 포트 번호에 접근 가능

## 포트 번호 종류

![07-well-known](https://user-images.githubusercontent.com/51018201/127729653-13366a19-0ae0-4b65-9f2d-2efd91a830c6.jpg)

Well-known 포트 – 잘 알려진 유명한 프로그램들이 어떤 포트를 쓰는지 지정되어 있음(잘 알아놔야 함)    
> ex) 웹 서버의 포트 번호 80번

![07-registerd](https://user-images.githubusercontent.com/51018201/127729656-e8091f79-2c6b-4fb6-b4b3-b2184f567097.jpg)

Registered 포트 – 조금은 유명한 포트들의 집합

![07-dynamic](https://user-images.githubusercontent.com/51018201/127729657-cd2adfd0-16de-4a13-b523-d4f8e1456ffd.jpg)

Dynamic 포트 – 일반 사용자는 이를 사용한다

## 프로그램의 연결 정보

- netsat -ano를 치면 현재 포트 활성 여부를 나타내는 활성 연결 테이블을 보여준다

## HTTP

Hyper Text Protocol

애플리케이션 계층 프로토콜이다

프로토콜은 약속이라고 보면 된다

<aside>
💡 HTTPS : HTTP에 인증과 보호 구조를 추가한 것

</aside>

## HTTP 상태 코드

서버로부터 요청 결과 전달

200: 성공 응답

400: 클라이언트 에러 응답

500: 서버 에러 응답

## HTTP 메서드

요청의 의도 전달

GET: 리소스 요청

PUT: 리소스 수정

POST: 리소스 생성

DELETE: 리소스 삭제 

## IP

Internet Protocol.

데이터 패킷이 네트워크를 통해 이동하고 올바른 대상에 도착할 수 있도록 데이터 패킷을 라우팅하고 주소를 지정하기 위한 프로토콜 또는 규칙의 집합

<aside>
💡 데이터 패킷: IP에서 사용하는 통신 단위                                                            라우팅: 네트워크 라우팅은 하나 이상의 네트워크에서 경로를 선택하는 프로세스

</aside>

단점

1) 서버가 패킷을 받을 수 있는 상태인지 확인 불가 → 신뢰성 하락

2) 데이터 손실 가능성 존재

3) 데이터 순서 보장X

보완 필요!! 

## TCP

Transmission Control Protocol

3-way handshake 개념으로 IP를 보완

Client → Server : SYN (연결 가능 상태인지 확인)

Server → Client: ACK + SYN (상태 확인 + 상태 전송)

Client → Server: ACK (상태 확인)

3가지 단계를 거친 후, Client ↔ Server 통신 시작

## 네트워크 계층

OSI 계층 모델, TCP/IP 계층 모델

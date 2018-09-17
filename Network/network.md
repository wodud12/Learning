# Network

## 1. what is a network?
- 네트워크는 다양한 정보통신 자원이 연결되어 일을 수행 데에 있어서 상호 정보교환을 수행 할 수 있게 해주는 연결 형태를 말한다.

## 2. LAN / WAN
- **LAN (Local Area Network)**  
논리적으로 가까운 거리에 위치한 네트워크 집합을 의미한다.
- **WAN (Wide Area Network)**  
최소 2개 이상의 LAN이 모여 이루는 넓은 범위의 네트워크 집합을 의미한다.

## 3. Protocol
 - 프로토콜이란 네트워크상에 있는 장비 사이에서 정확한 데이터의 송신과 수신을 위해 마련된 규칙들을 말한다.

## 4. TCP/IP
- TCP/IP는 Network Protocol의 한 종류로 Network 접속을 위한 통신 규약이라고 할 수 있다. TCP/IP는 TCP라는 Protocol과 IP라는 Protocol을 합쳐서 사용하는 것을 의미한다. IP는 192.168.114.0과 같은 주소 체계를 가지고 있고 TCP는 신뢰성 높은 데이터 송수신을 제공한다는 특징을 갖고 있다. Network에서 Network divice들이 상호 연결되기 위해서는 TCP/IP Protocol 토콜을 필수적으로 준수해야 한다.

## 5. OSI Layer 7
- OSI 7계층은 시스템의 동작을 계층을 활용하여 나타낸 것이다. OSI 7 계층을 활용하여 문제가 발생했을 때 각 단계별로 파악하여 물리적인 문제인지 응용프로그램과 관련이 있는 문제인지 등을 쉽게 파악할 수 있다.

- 7계층 – 응용 계층(Application):
응용 계층은 사용자와 가장 가까운 계층이다. 사용자가 이용하는 응용프로그램이 응용 계층에 해당된다고 할 수 있다. 대표적으로 구글 크롬(Google Chrome), 사파리(Safari), 스카이프(Skype) 등이 있다.

- 6계층 – 표현 계층(Presentation):
표현 계층은 네트워크 형식을 응용프로그램 형식으로 변환하거나 응용프로그램을 네트워크 형식으로 변환하는 계층이다. 대표적으로 데이터를 암호화, 복호화하는 과정이 표현 계층에서 이루어 진다.

- 5계층 – 세션 계층(Session):
세션 계층에서는 인증 및 서비스 계층이라고 할 수 있다. 응용 프로그램과의 연결을 담당한다.

- 4계층 – 전송 계층(Transport):
전송 계층에서는 Host간의 데이터 전송 조율을 담당한다. 데이터를 전송할 때 용량, 속도, 목적지 등을 처리한다. 대표적으로 TCP/IP Protocol이 있다.  
- 3계층 – 네트워크 계층(Network):
라우터 기능 대부분이 네트워크 계층에 자리잡는다. 가장 기본적으로 볼 때 이 계층은 다른 여러 라우터를 통한 라우팅을 비롯한 패킷 전달을 담당한다.

- 2계층 – 데이터 링크 계층(Data Link):
데이터 링크 계층은 연결된 노드 간의 데이터 전송을 제공하며 물리 계층의 오류 수정도 처리한다.
- 1계층 – 물리 계층(Physical)
물리 계층은 시스템의 물리적 표현을 나타낸다. 유선으로 연결된 케이블의 종류, 무선 주파수, 핀 배치 등 물리 요건에 대해 다룬다.

## 6. Server & Client

- Server와 Client는 Network에서 제공되는 서비스를 기준으로 서비스를 요청하는 Host가 Client, 서비를 제공하는 Host가 Server이다. 여기서 Host란 컴퓨팅 기능이 있는 시스템을 말한다.

- Server는 서비스를 주고받는 호스트들의 관계에서 특정 서비스를 제공하는 시스템이다. 일반적으로 서버는 클라이언트보다 먼저 실행 상태가 되어 클라이언트의 요청에 대기해야 한다. 클라이언트의 요청이 있을 때마다 서비스를 반복해서 제공해야 한다.

- Client는 서비스를 요청하는 시스템이다. 호스트는 다양한 서비스를 서로 주고받기 때문에 임의의 호스트가 클라이언트나 서버로 고정되지는 않는다. 이용하는 서비스의 종류에 따라서 클라이언트가 될 수도 있고, 서버가 될 수도 있다. 그러므로 특정 서비스를 기준으로 클라이언트와 서버라는 상대적 용어로 구분한다.
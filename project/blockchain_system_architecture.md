### 블록체인 적용 시스템 아키텍처

- Layer (낮은 계층순)
  1. hardware/infrastructure layer
  2. data layer
  3. network layer
  4. consensus layer
  5. application and presentation layer

<br>

### 블록체인 적용 시스템 아키텍처란

- 블록체인기술을 이용하여 기존의 서비스를 확장하여 저장하고 생산하는 데이터의 신뢰성을 증가시킨 형태의 어플리케이션 및 실행구조
- 기존의 웹서비스에서 이력관리에 필요한 데이터들을 블록체인에 기록하여 독립화 시키면 보안, 시스템적으로 안정된 구성을 가져감.

<br>

### 블록체인 아키텍처 구성요소

- 분산저장 네트워크
- 블록체인 데이터
- 합의 알고리즘
- 암호화폐, 수수료, 채굴
- 지갑
- 스마트컨트랙트, SDK
- 어플리케이션 SDK
- 보안기술 등..

<br>

### 블록체인 웹서비스 구조

- 어플리케이션 사용자는 웹브라우저, 모바일 등을 통하여 웹서버에 접근함
- 웹서버 접근시 HTTP로 표현된 REST API를 사용해 리소스 요청을 수행
- 웹서버는 블록체인 네트워크에 연결되어 블록체인 클라이언트 역할을 수행
- 웹서버는 블록체인 네트워크의 스마트 컨트랙트를 수행하여 결과를 사용자에게 응답합.

<br>

### 하이퍼래저 스마트 컨트랙트 연동개발 순서

1. 웹 UI 작성: 사용자 요구사항에 맞도록 UI를 설계하고 작성
2. 웹서버 구현: 사용할 Chaincode에 맞게 라우팅과 연동부를 작성
3. 구동 및 테스트: 웹서버가 정상적으로 구동하는지 페이지를 테스트

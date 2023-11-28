## 사전미션

1. 컨테이너 기술이란 무엇입니까?
   해운 업계에서 컨테이너를 통해 제품들을 한 번에 배송하는 것처럼 소프트웨어 개발환경에서도 개발에서부터 애플리케이션 실행까지 한 번에 제공하는 기술을 말한다.

2. 도커란 무엇입니까?
   도커란 어플리케이션을 쉽게 패키징할 수 있는 툴이다. 컨테이너라고 불리는 하나의 작은 소프트웨어 유닛 안에 컨테이너 이미지를 묶어서 다른 서버에 쉽게 배포하고 안정적으로 구동시킨다.

3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?

- 도커 파일: 도커 이미지를 빌드하기 위한 지침을 기술한 텍스트 파일이다. 도커 파일에는 베이스 이미지(기본 이미지), 추가적으로 설치할 소프트웨어, 설정 등이 정의되어 있다.
- 도커 이미지: 도커 파일에 정의된 내용을 기반으로 만들어진 가볍고 독립적인 실팽 가능한 패키지이다. 이미지는 파일 시스템, 라이브러리 등 애플리케이션 실행에 필요한 모든 것을 포함한다.
- 도커 컨테이너: 도커 이미지의 인스턴스로, 실행중인 프로세스이다.

  도커 파일은 이미지를 만들기 위한 설계도이고, 이미지는 컨테이너를 실행하기 위한 패키지이며, 컨테이너는 이미지의 인스턴스로 실행 중인 애플리케이션입니다.

4. [실전 미션] 도커 설치하기
## 1. What is Spring Framework?
스프링 프레임워크는 자바 플랫폼을 위한 오픈 소스 애플리케이션 프레임워크로서 스프링이라고 함.

스프링은 EJB(Enterprise Java Beans: 시스템 구현을 위한 서버측 컴포넌트 모델) 컨테이너 사용으로 인한 개발 생산성과 유지 보수성 저하와 테스트와 배포의 어려움을 해결해줌.

## 2. Spring Framework Features
- 경랑 컨테이너로서 자바 객체를 직접 관리
- POJO(Plain Old Java Object) 방식
- 제어반전(IoC: Inversion of Control) 기반
- 의존성 주입(DI: Dependency Injection) 기반
- 관점 지향 프로그래밍(AOP: Aspect-Oriented Programming) 기반

## 3. What is Spring Boot?
스프링 프레임워크 기반 프로젝트를 어려운 설정이나, WAS에 대한 설정 없이 바로 개발에 들어갈 수 있도록 만든 프레임워크

스프링 프레임워크를 사용하면 많은 xml 파일들을 작성해야하고, 기존에 사용했던 설정들을 복사 붙여넣기하거나<br> 검색을 통해 일일이 설정을 해야함

스프링 부트를 사용하면 이러한 설정 없이 쉽고 빠르게 프레임워크 사용 가능

## 4. Spring Boot Features
- 번거로운 xml 설정 x
- 일일히 관련 라이브러리를 찾아 추가할 필요 없이 spring-boot-starter-web 의존성을 추가하면 관련 라이브러리를 받아옴
- 톰캣 내장
- 설정의 자동화 (@SpringApplication)
- 라이브러리 버전 자동 관리
- 단독으로 실행이 가능한 jar

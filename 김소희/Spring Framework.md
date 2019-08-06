## Spring Framework

###    1. 개요

필요한 부분만 가져다 사용할 수 있도록 모듈화된 경량솔루션이다.

IoC, JDBC, AOP, MVC 등을 함께 사용할 수 있다.

스프링은 프레임워크에 의존적이지 않으므로 비침투적이다.

-> 스프링의 의존성 주입은 모두 XML로 한다.

* POJO(Plain Old Java Object)란 단순히 평범한 자바빈즈 객체를 의미한다.

* XML

* Annotation@

* Spring AOP (Aspect Oriented Programming)

* Spring MVC (Model, View, Controller)

  web.xml (dispatcher, filter)

  spring.xml (ViewResolver)

  servlet = controller
  
  
  
  ### 2. 특징
  
  

- 경량컨테이터

  각각의 객체 생성, 소멸 등을 관리하며 스프링으로부터 필요한 부분만 얻어올 수 있다.

- 제어 역행 (IoC : Inversion of Control)

  어플리케이션의 느슨한 결합을 가능하게 함

  컨트롤의 제어권이 사용자가 아니라 프레임워크에 있어 필요에 따라 스프링에서 사용자의 코드를 호출

- 의존성 주입 (DI : Dependency Injection)

  각 계층이나 서비스들 간에 의존성이 존재할 경우 프레임워크가 서로 연결시켜준다.

- 관점지향 프로그래밍 (AOP : Aspect-Oriented Programming)

  트랜잭션이나 로깅, 보안과 같이 여러 모듈에서 공통적으로 사용하는 기능의 경우 해당 기능을 분리하여 관리할 수 있다.

- 애플리케이션 객체의 생명 주기와 설정을 포함하고 관리

- 트랜잭션 관리 프레임워크

  추상화 된 트랜잭션 관리를 지원하며 설정파일(xml, java, property 등)

- 모델-뷰-컨트롤러 패턴

  DispatcherServlet이 Controller 역할을 담당하여 각종 요청들을 적절한 서비스에 분산시켜주며 이를 각 서비스들이 처리하여 결과를 생성하고, 다양한 형식의 View 서비스들로 화면에 표시한다.

- 배치 프레임워크

  특정 시간대에 실행하거나 대용량 자료를 처리하는 데 쓰이는 일괄처리(Batch Processing)을 지원하는 프레임워크를 제공한다.

- 공통 부분의 소스 코딩이 용이하며 확장성도 높다.

# 1. What is Spring Framework
  : 사전지식이 필요 : Java, JSP 을 학습하고 배우는 것을 추천함.
  ## 주요기능
  1. DI(Dependency Injection: 필요한 기능마다 주입하여 사용)
  2. AOP(Aspect-Oriented Programming: 관점지향 프로그램, 주요부분을 사용하고 공통된 부분은 띠었다 붙였다 함)
  3. MVC(Model View Control: 코드를 분리함)
  4. JDBC(Java DataBase Connector: DB를 연결)

# 2. 프레임워크란?
  : 개발자들이 편리하게 작업하는 틀
  예시) 네비게이션을 사용하여 길을 찾는것(프레임워크)과 네비없이 지도나 이정표를 보고 길을 찾아가는 경우.

# 3. 스프링 프레임워크의 모듈
  1. spring-core : 스프링의 핵심인 DI(Dependency Injection)와 IOC(Onversion of Control)를 제공
  2. spring-app : AOP구현 기능 제공
  3. spring-jdbc : 데이터베이스를 쉽게 다룰 수 있는 기능 제공
  4. spring-tx : 스프링에서 제공하는 트랜잭션 관련 기능 제공
  5. spring-webmvc : 컨트롤러(Controller)와 뷰(View)를 이용한 스프링MVC 구현 기능 제공
  > 스프링 프레임워크에서 제공하는 모듈을 사용하려면, 모듈에 대한 의존설정을 개발 프로젝트에 XML 파일등을 이용해서 개발자가 해야 한다.
  
# 4. 스프링 컨테이너(IoC)
  : 스프링에서 객체를 생성하고 조립하는 컨테이너, 생섣된 객체를 빈(Bean)이라고 부름.

# SpringBootStudy
실전 스프링 부트 REST API개발 JPA + MySQL (개정판)으로 Study

소스에 주석으로 들어갈 수 없는 내용을 README.md에 작성할 계획입니다.
================================================================================================================
구성요소 pom.xml -> 메이븐 프로젝트 빌드 파일

/src/main/java ->자바소스 경로

/src/main/java/DevProjectApplication.java -> 애플리케이션을 시작할 수 있는 스프링 구성 메인클래스 소스파일

/src/main/java/ServletInitializer.java -> Project 생성시 Packging을 War로 선택하였을때 생성되는 파일

/src/main/resources -> 리소스 파일 경로

/src/main/resources/application.properties -> 애플리케이션에 사용할 여러 가지 프로퍼티 정의

/src/main/resources/static -> 스타일 시트, 자바스크립트, 이미지등의 정적 리소스 파일 경로

/src/main/resources/template -> 뷰 템플릿 파일경로
================================================================================================================
스프링 스타터 프로젝트 의존성 : 스트링 부트는 프로젝트의 의존성을 설정하는 대화창을 제공한다.
================================================================================================================
lombok

롬복(Lombok)을 활용하면 약갼의 애너테이션 설정만으로 소스 코드가 컴파일될 때 자동으로 추가 코드를 만들 수 있다.

@Getter/@Setter => 객체의 게터 세터를 생성한다.

@ToString => toString()메서드를 생성한다.

@EqualsAndHashCode => 자바의 equals() 메서드와 hashCode()메서드를 생성한다. 
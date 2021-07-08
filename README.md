# Java-Spring-Simple-Todo-Gradle

java, jpa 를 이용하여 간단한 TODO api server 를 구현합니다.

## mvc , repository 패턴을 이용하여 해당 api 서버를 구현합니다.

## model 
entity 와 모델 , request 부분을 추상화하여 필요한 정보를 client 로 부터 받고

이를 디비에 저장합니다.

## controller

client 와 연동할수있도록 severlet 부분을 엔드포인트 로써 구현합니다.

service 에서 정의한 비즈니스 로직을 이용하여 클라이언트에게 보여줄수있는 뷰로서의 역할입니다.

## service 

todo server 에 필요한 비즈니스 로직을 구현합니다.

jpa를 이용하여 orm 객체를 사용

## repository

jpa 를 인터페이스로 두어 ORM 을 매핑한다.


## Gradle 빌드툴

gradle 빌드 툴을 이용하여 해당 spring 서버의 필요한 lib 포트 넘버 등을 정의하여 정의 합니다.

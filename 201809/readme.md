
## 09 . 13 Thursday

### 웹 서버(Web Server)와 WAS(Web Application Server)를 학습했다 (Evernote 메모 18.09.13)
+ 웹 서버의 기능을 정리했다.
+ 웹 애플리케이션 서버(WAS)가 load balancer 또는 reverse proxy 통해 적합한 WAS에서 클라이언트 요청 받는 방법을 부분적으로 이해할 수 있었다.
+ 회사 서비스의 프록시 서버 역할을 개념적으로 더 이해할 수 있는 기회가 되었다.

### JSP를 학습했다 (Evernote 메모 18.09.13)
+ JSP의 기능을 정리했다.
+ 클라이언트 요청에 의해 동적으로 생성된 JSP 파일이 웹 브라우저에 표시될 수 있기 까지 동작과정을 이해할 수 있었다.

---
<br>

## 09 . 14 Friday

### 토비의 스프링 1장 오브젝트와 의존관계 복습 (Evernote 메모 18.09.07 - 18.09.10)
+ 모르는 개념과 정리하지 못한 내용이 있는지 확인하고 사용 이유와 기존 또는 유사한 개념과 어떤 점이 다른지 이해하고 정리하기 위한 학습을 진행했다.

---
<br>

## 09 . 15 Saturday

### [오브젝트와 의존관계 그리고 스프링3 1부](https://www.youtube.com/watch?v=SZydc3BS--s) tutorials 학습
+ 학습내용 [구현](https://github.com/nttejun/lecture-tutorial/tree/master/spring-denpendency/src/main/java/spring/dependency)

---
<br>

## 09 . 16 Sunday
 
### [오브젝트와 의존관계 그리고 스프링3 2부](https://www.youtube.com/watch?v=JI7RNrWqp7k) DaoFactory 분리까지 tutorials 학습 (Evernote 메모 18.09.16) 
+ 학습내용 [구현](https://github.com/nttejun/lecture-tutorial/tree/master/spring-denpendency/src/main/java/spring/dependency)
+ makeConnection 중복제거 - Connection 생성 방식 상속 - 위임 - 인터페이스 도입 - 의존성 주입 순서로 코드를 변경하면서 어떻게 구현해야 하는지 부분적으로 이해할 수 있었다.

---
<br>

## 09 . 17 Monday

### [오브젝트와 의존관계 그리고 스프링3 2부](https://www.youtube.com/watch?v=JI7RNrWqp7k) tutorials 학습 (Evernote 메모 18.09.17)
+ Dependency Inject 사용한 코드에서 Spring Inversion of control 사용하는 코드로 변경하면서 사용방법에 대해 이해할 수 있었다.

---
<br>

## 09 . 18 Tuesday

### 사내 서비스 management 서버 인증서 만료 상태 메서드 확인
+ 서버에서 응답받는 인증서 만료 상태를 Calendar, Date Class 등을 이용하여 d-day 값 반환받도록 구현방법 확인

---
<br>

## 09 . 19 Wednesday

### 토비의 스프링 3.0 8장 내용 부분 학습 (Evernote 메모 18.09.19)
+ 스프링의 정의와 스프링을 사용하는 목적에 대한 학습을 진행했다

---
<br>

## 09 . 20 Thursday

### 사전에 약속한 사원 회식이 있던 날.

---
<br>

## 09 . 21 Friday

### 지인 1명과 추석 연휴 기간 동안 작은 프로젝트를 진행하기로 했다.
+ AWS RDS(MySQL) 서버 생성 및 지인 권한 부여를 완료했다.

---
<br>

## 09 . 22 Saturday

### AWS RDS 서버 생성 및 DB 권한 부여에서 발생한 이슈에 대해 정리했다.
+ RDS 서버 외부 접속 시 [ping 연결실패 이슈](http://wjjeong.tistory.com/11) 내용을 블로그에 정리했다.
+ [MySQL 권한부여 실패 이슈](http://wjjeong.tistory.com/10) 내용을 블로그에 정리했다.

### starter 프로젝트를 진행했다.
+ 사용자, 게시판 테이블 추가 (테이블 정의 문서 참고)
+ [AWS RDS(MySQL) 한글 깨짐 이슈](http://wjjeong.tistory.com/12) 내용을 블로그에 정리했다.

---
<br>

## 09 . 23 Sunday

### starter 프로젝트를 진행했다.
+ AWS RDS 서버 접근 권한이 있는 사용자 계정의 접속 실패 문제를 해결했다.
    + 문제 해결보다 [문제가 발생한 원인에 대한 반성](http://wjjeong.tistory.com/13)이 중요하여 내용을 블로그에 정리했다.

---
<br>

## 09 . 24 Monday

### starter 프로젝트 [API 개발](https://github.com/nttejun/starter-api/tree/master/src/main/java/starter/api)을 진행했다.
+ 지인 1명과 커뮤니케이션 효율을 높이기 위해 MySQL Comment를 추가했다.
+ SpringBoot JPA, Builder 패턴으로 아이디 조회, 회원등록 테스트 코드를 구현했다.

---
<br>

## 09 . 25 Tuesday

### starter 프로젝트 [API 개발](https://github.com/nttejun/starter-api)을 진행했다.
+ SpringBoot JPA, Builder 패턴으로 게시판 생성 기능을 구현했다.

---
<br>


## 09 . 26 Wednesday

### starter 프로젝트 [API 개발](https://github.com/nttejun/starter-api)을 진행했다.
+ Bootstrap 적용했다.
+ 템플릿 엔진 thymeleaf 사용하여 화면을 구현했다.

---
<br>

## 09 . 27 Thursday
### 토비의 스프링 3.0 8장 내용 부분 학습 (Evernote 메모 18.09.27)
+ 엔터프라이즈 개발에 스프링 프레임워크를 사용하는 이유와 스프링이 기술적으로 지향하는 부분에 대한 내용을 정리했다.

---
<br>


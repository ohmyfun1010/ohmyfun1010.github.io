# 프로젝트 설명

본 프로젝트는 게시물을 올리고 내리며 게시글을 다양한 사용자들이 공유할 수 있는 게시판입니다.

### 개발 인원

1명

### 담당 업무

오라클 DBMS 연동을 통한 로그인, 회원가입, CRUD 처리, 페이징 처리

### 프로젝트 목표

사용자들이 실시간으로 다양한 정보를 공유할 수 있는 게시판 홈페이지 제작

### 구현 기능

     - 회원가입
     - 로그인
     - CRUD
     - 페이징 
     

### 개발 도구

     - Jdk : 8 버전
     - Spring framework : spring 5
     - 웹서버 : Apache
     - WAS : Tomcat 9.0
     - Maven : 3.2.1
<br>

# 데이터베이스 테이블 설계
![DB](./images/DB.png)

<br>

# 화면 구성

## 메인 화면
<img src="images/main.png" width="800">

<br>

## 회원가입 및 로그인 화면
### 회원가입 화면
<img src="images/join.png" width="800">

<br>

### 회원가입 유효성 검사
<img src="images/joincheck.png" width="500">


1.기본 제공되는 유효성 검사 어노테이션 활용<br>
2.추가적인 유효성 검사(비밀번호 확인절차)는 Validator 활용<br>
3.아이디 중복 확인 절차는 ajax통신을 활용하여 중복 버튼을 눌렀을 때 입력한 데이터의 존재유무를 판단후 restcontroller를 활용하여 true,false값을 반환받아 중복 유무 확인


<br>
### 로그인 화면
<img src="images/login.png" width="800">

<br>

### 로그인 유효성 검사
<img src="images/loginchecks.png" width="500">


## 게시판 화면
### 자유 및 유머 게시판
<img src="images/free.png" width="500"><img src="images/funny.png" width="500">

<br>

### 그림 및 게시판
<img src="images/draw.png" width="500"><img src="images/sports.png" width="500">

<br>

### 게시글 화면
<img src="images/board.png" width="800">

<br>

### 게시글 수정 화면
<img src="images/boardupdate.png" width="800">




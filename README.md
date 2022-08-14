section.split {
    overflow: visible;
    display: grid;
    grid-template-columns: 500px 500px;
    grid-template-rows: 100px auto;
    grid-template-areas: 
        "slideheading slideheading"
        "leftpanel rightpanel";
}
/* debug */
section.split h3, 
section.split .ldiv, 
section.split .rdiv { border: 1.5pt dashed dimgray; }
section.split h3 {
    grid-area: slideheading;
    font-size: 50px;
}
section.split .ldiv { grid-area: leftpanel; }
section.split .rdiv { grid-area: rightpanel; }
### A split slide
<!-- _class: split -->

<div class=ldiv>

#### Title for the left panel
- listed item
- listed item
- listed item
</div>
<div class=rdiv>

#### Title for the right panel
- listed item
- listed item
- listed item
</div>

### 개발자 최효빈의 포트폴리오
##### Java 백엔드 웹개발자 최효빈입니다.

<!--모델 : https://roseline.oopy.io/resume-->


---



### 📞 Contact.
**Naver.** gyqls234@naver.com       
**Gmail.** gyqls234@gmail.com   

&nbsp;
---
&nbsp;

    
### 📺 Channel.

**Blog.** [https://atomicliquors.tistory.com/](https://atomicliquors.tistory.com/)

**Github.**  [https://github.com/AtomicLiquors](https://github.com/AtomicLiquors)

</div>


---


### Skills.  
(Java를 메인으로 하고, 공고를 보고 필요한 스택만 표시해서 제출.)


<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=Java&logoColor=white">
<div style="display: flex;">
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
<img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
<img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
</div>
  

<div style="display: flex;">
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> 
 
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
  <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">
  <br>
  
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/fontawesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white">
  </div>
  
&nbsp;
---
&nbsp;
### Projects

### [팀 프로젝트] 로컬 카페 추천 웹사이트
유저들이 핫플레이스 카페들을 리스트로 모아 공유하고, 방문 후기를 남기는 웹사이트입니다.  
'22.07.01 - '22.07.26 (3주)   
  
- Spring 이용 MVC 모델 적용  
- Ajax 비동기 통신을 통해 회원 및 카페(사업장) CRUD
- 파일업로드 구현

사용 기술 :
<div style="display: flex;">
    <img src="https://img.shields.io/badge/java-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/spring-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/html-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/css-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/javascript-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/thymeleaf-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/mysql-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/mybatis-edeae8?style=for-the-badge&logo=Java&logoColor=black">
</div>

Java, Spring
View : Html, CSS, Ajax, Thymeleaf 
DB : MySQL, MyBatis  
IDE : STS4

GitHub: https://github.com/HyebinPark96/CherryPick  
  
<!--
**Skills**  
Java. Spring

View : Html, CSS, Ajax, Thymeleaf 
DB : MySQL, MyBatis  
IDE : STS4-->

PostgreSQL Prisma GraphQL Express.js React Next.js TypeScript Material UI  ElasticSearch

<!-- Project REadme로.
**역할 분담**  
김서하  
● DB 설계 및 클라우드 DB 관리  
● Kakaomap api로 지도 데이터 적용  
● Ajax 비동기 통신 활용한 카페 , 북마크 crud   

박혜빈  
● 개발환경 구축 및 형상관리  
● Spring Security 적용 권한 및 인증 설정 / Bcrypt 로 패스워드 해싱  
● HttpSession로 유저 정보 관리  
● SmartEditor 리뷰 작성 및 게시판 구현  
● jQuery / Ajax / Jackson 라이브러리 사용으로 JSON 데이터 변환 및 비동기 통신  
● RESTful API 설계  
● ErrorController 인터페이스 구현으로 에러페이지 커스터마이징  
● MyBatis 동적 쿼리 사용으로 분기처리  
  
최효빈  
● 프론트엔드 : css 디자인 및 js/jquery 이용 동적 엘리먼트 제어  
● 파일업로드 구현 및 Drag & Drop 방식과 이미지 미리보기 구현  
● Ajax 비동기 통신을 통한 카페(사업장) 등록 및 수정 구현  -->
  
&nbsp;    
&nbsp;      

### [팀 프로젝트] 음악 웹사이트
음악을 주제로 대화하며, 댓글과 좋아요 등 SNS기능이 구현된 게시판 웹사이트입니다.  
'22.05.01 - '22.05.17 (2주)
  &nbsp;  

Tomcat, Java, JSP/servlet, j-Query, MySQL (개발인원: 4명)
<div style="display: flex;">
    <img src="https://img.shields.io/badge/java-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/spring-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/html-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/css-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/ajax-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/thymeleaf-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/mysql-edeae8?style=for-the-badge&logo=Java&logoColor=black">
    <img src="https://img.shields.io/badge/mybatis-edeae8?style=for-the-badge&logo=Java&logoColor=black">
</div>

- Jsp
- [팀장] 화면설계 및 DB설계, 프론트엔드
- 네이버 아이디 로그인 구현

GitHub: https://github.com/AtomicLiquors/jsp-music-website/

&nbsp;  
&nbsp;    

### [팀 프로젝트] 사무용 캘린더
캘린더 프로그램입니다.  
개발기간 : '22.03.15 - '22.03.31(2주)  
개발인원: 3명  

- Java AWT/Swing 기반 GUI
- [팀장] 화면설계 및 DB설계 
- Java GUI 달력 구현 및 D-Day 기능
- JDBC, MySQL 이용 회원등록/로그인/일정 등록 등 DB 연동 기능


사용 기술 : 
<img src="https://img.shields.io/badge/java-edeae8?style=for-the-badge&logo=Java&logoColor=black">
<img src="https://img.shields.io/badge/mysql-edeae8?style=for-the-badge&logo=Java&logoColor=black">

GitHub: https://github.com/AtomicLiquors/java-calendar

&nbsp;
---
&nbsp;
### Experience

- 컴퓨터활용능력(1급) 취득 ('22.06.17 / 22201030532W)
- 정보처리기사 자격증 취득 ('22.06.17 / 22201030532W)
- 부산IT교육센터 [NCS] (디지털컨버전스)자바 기반 클라우드 융합 응용SW개발 과정 수료 ('22.01.17 - '22.07.26)

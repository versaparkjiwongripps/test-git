# 0. 수업정리 - notion, git TIL

## 1.web application program

-인터넷,인트라넷 상에서 데이터를 처리하는 비즈니스
로직을 포함하는 프로그램

## 2.웹 애플리케이션 실행 환경

● Front-end(UI, Client)

---

html5 : 뼈대,틀
css : 스타일
js(javascript) : 이벤트
ES5/ES6
JQUERY, AJAX , JSON...

---

웹 브라우저 : .html, .htm(같음)

Script 언어? -혼자서는 실행이 불가능(어딘가에 포함이 되어야함)

#### 1.Client Script

-JavaScript
-VBScript

#### 2. Server Script

-PHP
-JSP
-ASP

## ●Back-end(server)

#### 웹서버는 서버에서 실행하는 언어따라 종류가 나뉜다

## JavaBeans : DTO, DAO, Service

WAS(tomcat, jeus,weblogic...)
이런 키워드가 실행되는 확장자는 보통 : .jsp .java 이다.

## DB(DataBase)

oracle, MySQL ,DB2
DB연동은 서버를 통해서 연결해야함,

---

SQL-CRUD

## 프로그램 코드 실행방법

-컴파일러--> 실행코드 --> 실행 (프로그램 코드를 한번에 다 읽고 실행) -인터프리터 --> 실행코드 -->실행(코드를 한번에 읽지 않고 한줄한줄 읽어서 실행) -하이브리드 : 컴파일러 --> 바이트코드 --> 인터프리터 --> 실행코드 -->실행(둘다포함) ex)java

## 5.수업의 결과물 ==>>팀 프로젝트

-자기소개 : 이름, 전공, 경험,나이,주소
<br>-팀장 추천

------------------------------------2------------------------------------------------

## 깃허브

모든 과정을 로컬 저장소(Local Repository)에 저장하는 것이 아니라, 스테이징 영역을 통해 저장해야 하는 부분을 정리할 수 있다.

작업 디렉토리 : 코딩하는 공간
스테이징 영역 : 임시 저장 공간
로컬 저장소(Local Repository) : 실제 로컬에 저장되는 공간
원격 저장소(Remote Repository) : 내가 저장한 변경 내역을 다른 사람과 공유할 수 있는 원격 공간

강의실 commit(로컬저장소) 10개(git) push >> repository(github 원격저장소) >> pull 20개 집

Untracked : 내가 새로 만든 파일(Git은 모름)
Staged : Untracked 파일을 스테이징 영역에 올린 상태
Unmodified : 스테이징 영역에서 Commit 되었고, 아무런 변경 사항이 없을 때
Modified : Unmodified 파일에 변경 사항이 있을 때 (다시 스테이징 영역에 올려야함)

Installer 다운로드 권장 각 다른 버전을 관리할때는 prtable 버전으로 관리

cd
cd.. 뒤로가기
dir /w 조회


#### git clone 주소  클론폴더명

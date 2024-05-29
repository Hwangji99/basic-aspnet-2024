# basic-aspnet-2024
IoT 개발자 과정  ASP.NET 리포지토리

## 1일차(2024-05-29)
- 웹 기술 개요
    - World Wide Web (Web은 인터넷이 아니라 인터넷의 한 파트)
    - Full Stack
    - Front-end : 웹사이트 화면으로 사람들에게 보이는 부분 기술
    - Back-end : 웹사이트 뒤에서 동작하는 서버 기술
    - Server-Operation : HW, OS, SW 등 운영(클라우드)

- 업무용 웹 사이트 참조
    - https://www.ecount.com/kr/ECK/ECK004M_CN.aspx

- Front-end(클라이언트)
    - HTML5
    - CSS3
    - Javascript()

- Back-end(서버)
    1. Java - Spring, Spring Boot, JSP, EJB ...
    6. Javascript - Node.js, Express ...
    3. Python - Django, Flask, fastAPI ...
    2. C# - ASP.NET
    4. Ruby - Ruby on rails
    5. C - cgi,fasCGI ...
    7. PHP

- 개발
    - 프로트엔드 전부 + 백엔드 여러개 중 하나 + DB
    - 웹 브라우저에서 F12(개발자 도구)
    - VS Code 플러그인
        - HTML Code Snippet
        - Live Server

- HTML 주요 기능
    - 장치 접근
    - 오프라인 저장소
    - 시맨틱
    - CSS3 스타일 시트

- HTML5
    - XML(eXtensible Markup Language)이 웹페이지를 구성하기 위한 선행기술, 너무 복잡해서 간략화 시킨 것
    - Hyper Text Markup Language
    - 기본적으로 확장자 .html
    - Tip! lorem 탭, 긴 샘플텍스트 생성
    - 기본 태그 (요소, body)
        - HTML 페이지즐 구성하는 각 부품(제목, 본문, 이미지 등)
        - 내용을 가질 수 있는 요소
        - 내용을 가질 수 없는 요소
        - h1 ~ h6 = 제목(마크다운 #, ##와 동일)
        - p : 일반문장
        - div : 그룹화 구분자, 아주 중요(CSS 연계 디자인)
        - img : 이미지 태그
        - br : 한줄 내리기(Enter)
        - hr : 가로선
        - 특수문자 : & ; 사이에 영문자로 표시(너무 많음)
        - strong 또는 b : Bold체(굵기)
        - em : Italic체(기울기)
        - mark : 형광펜 효과
        - small, sub, sup : 글자 작게, 아래첨자, 윗첨자
        - u, strike : 밑줄, 취소선
        - a : 웹페이지 링크(중요!)
        - ul, ol > li : 순서없는 목록, 순번있는 목록
        - table, tr, th, td : 테이블 만드는 태그
        - audio, video : 오디오, 비디오
        - object, embed : 객체 추가

    - HTML + CSS + Javascript
        - 내부 스타일, 외부 스타일 추가, 인라인 스타일
        - 내부 스크립트, 외부 스크립트 추가, 인라인 스크립트

    - 오류, 디버그
        - F12 개발자 도구로 활용

    - 양식 태그 (body > form 안에 사용 필수) 
        - 요소를 만들 때 사용하는 작성 방법
        - front-end에서 입력한 내용이 back-end로 보내기 위한 관문
        - form 을 반드시 사용!!
        - input
            - type ="text" : 텍스트 박스
            - type ="password" : 비밀번호 박스
            - type ="button" : 일반 버튼
            - type ="submit" : 제출(!)
            - checkbox : 체크박스
            - radio : 라디오 버튼
            - file : 파일 업로드
            - image : 이미지(img와 유사)
            - reset : 폼 내의 입력 양식 태그 값 초기화
            - hidden : 숨김 값(유용하게 사용!!!)
        - textarea : 여러 행 텍스트 입력
        - select, option : 콤보 박스
        - filedset : 그룹 박스
        - submit 클릭 loopback(값 전달)발생
        - 값 전달 방법
            - GET : URL뒤 ?다음에 key=value&key=value ... 데이터 전달
            - POST : 화면 뒤로 숨겨서 데이터 전달 방식
    
    - 공간 구분 태그
        - div : 블록 형식으로 공간 분할(행간으로)
        - span : 인라인 형식으로 공간 분할(한줄로)

## 2일차(2024-05-30)
- HTML5
    - 시맨틱 태그
- CSS3
    - 웹 디자인 핵심
- Javascript 

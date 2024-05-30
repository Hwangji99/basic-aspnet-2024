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
    - 통신 기능
    - 웹의 성능 극대화 및 통합

- HTML5
    - XML(eXtensible Markup Language)이 웹페이지를 구성하기 위한 선행기술, 너무 복잡해서 간략화 시킨 것
    - Hyper Text Markup Language
    - 기본적으로 확장자 .html
    - Tip! lorem 탭, 긴 샘플텍스트 생성
    - 기본 태그 (요소, body)
        - HTML 페이지즐 구성하는 각 부품(제목, 본문, 이미지 등)
        - 내용을 가질 수 있는 요소 : <요소이름>내용</요소이름>
        - 내용을 가질 수 없는 요소 : <요소이름>
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
        - 웹브라우저 F12 개발자 도구로 활용

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
            - GET : URL뒤 ?다음에 **key=value&key=value** ... 데이터 전달
            - POST : 화면 뒤로 숨겨서 데이터 전달 방식
    
    - 공간 구분 태그
        - div : 블록 형식으로 공간 분할(행간으로)
        - span : 인라인 형식으로 공간 분할(한줄로)

## 2일차(2024-05-30)
- 보기 > 자동줄바꿈(매우 유용) ★★★
- HTML5
    - 시맨틱 웹 
        - 시맨틱 태그로 화면 구조를 잡는 웹구성 방식 
        - 프로그램이 코드를 읽고 의미를 인식할 수 있는 지능형 웹
        - 시맨틱 태그를 div로 바꿔도 똑같이 동작하기 때문에 요새는 많이 사용안해서 걷어내고 있는 추세
        - 시맨틱 태그
            - header : 머리말(페이지 제목, 페이지 소개)
            - nav : 하이퍼링크들을 모아둔 내비게이션
            - aside : 본문에 흐름을 벗어나는 노트나 팁
            - section : 문서의 장이나 절에 해당하는 내용
            - article : 본문과 독립적인 콘텐츠 영역
            - footer : 꼬리말(저자나 저작권 정보)
- CSS3
    - 웹 디자인 핵심, Cascading Style Sheets
    - 상단에서부터 <body> 부터 하위에 태글들에 계속해서 적용되는 스타일이라는 의미
    - 선택자에게 주어지는 디자인 속성
    - 선택자(selector) : CSS3에서 특정 HTML 태그를 선택할 때 사용
        - 기본 선택자 
            - 전체 선택자(*) : HTML 페이지 내부의 태그를 모두 선택
            - 태그 선택자(태그) : HTML 페이지 내부의 특정 태그를 모두 선택
            - 아이디 선택자(#아이디) : 특정 태그 하나를 선택할 때 사용(id 속성은 웹 페이지 내부에서 중복X)
            - 클래스 선택자(.클래스) : 특정 클래스가 있는 태그 선택
        - 속성 선택자
            - 선택자[속성] : 특정한 속성이 있는 태그 선택
            - 선택자[속성=값] : 특정한 속성 내부 값이 특정 값과 같은 태그 선택
        - 후손 선택자 : 밑에 모든 태그
        - 자손 선택자 : 바로 밑에 태그만
        - 반응 선택자
            - hover : 사용자가 마우스 커서를 올린 태그 선택
            - active : 사용자가 마우스로 클릭한 태그 선택
    - 속성(property)
    - 레이아웃
        - HTML 만으로는 화면 레이아웃이 만들어지지 않음
        - 중앙정렬, 원트루, 고정바 ...
    - 반응형 웹(Responsive Web)
        - 웹 페이지 하나로도 데스크톱, 태블릿PC, 스마트폰에 맞게 디자인이 자동으로 반응해서 변경되는 웹 페이지
        - 장점: 개발 효율성, 유지 보수 용이
        - 미디어 쿼리(media query)를 사용해 개발
        ```html
        <meta name='viewport' content='width=device - width, initial - scale = 1'>
        ```
        - @media 태그 : 디바이스 종류별로 CSS 따로 디자인 가능
        
- Javascript 

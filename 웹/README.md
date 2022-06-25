# :triangular_flag_on_post: 웹

| 목차 | 내용 |
| --- | --- |
| :one: | [웹 서비스](#pencil2-웹-서비스) |
| :two: | [웹 서버](#pencil2-웹-서버) |
| :three: | [웹 기술](#pencil2-웹-기술) |
| `기출` | [Q1. AJAX가 무엇인지 예를 들어 설명하시오.](#heavy_check_mark-q1-ajax가-무엇인지-예를-들어-설명하시오)<br/>[Q2. 웹 브라우저 검색창에서 키워드를 입력하면 결과가 나오는 과정을 설명하시오.](#heavy_check_mark-q2-웹-브라우저-검색창에서-키워드를-입력하면-결과가-나오는-과정을-설명하시오) |

<br/>


### :pencil2: 웹 서비스
:arrow_forward: 기존의 웹
* HTTP, HTML, URL과 같은 기술을 통해 인터넷에 분산되어 있는 정보 자원들에 대하여 표준화된 접근과 정보 표현 방법

<br/>

:arrow_forward: 웹서비스
* `XML`과 `인터넷 프로토콜`을 통해 `표준화된 방식으로 상호작용`
* 컴포넌트, 인터넷, XML등의 기술을 새로운 개념으로 적용하는 방법론
* 기본적인 표준 인프라가 구축되어 있는 경우에는 그것을 바탕으로 무궁무진한 활용이 가능

<br/>

:arrow_forward: 특징
* **플랫폼에 독립적**
* 디바이스 및 위치에 독립적
* 동적인 기능(Dynamic Function)
* 비용 효율적
* 기존 시스템(Legacy System)에 적용

<br/>

:arrow_forward: 웹서비스의 동작 흐름

  ![image](https://user-images.githubusercontent.com/42609725/175790309-ca89da69-cda8-49f6-aab8-e645afd75812.png)

<br/><br/>

### :pencil2: 웹 서버

:arrow_forward: 웹서버의 동작 흐름

  ![image](https://user-images.githubusercontent.com/42609725/175790365-976c143e-447e-4057-b9b5-4b7ad240d435.png)

<br/>

:arrow_forward: 정적 웹페이지와 동적 웹페이지

| 정적 웹페이지 | 동적 웹페이지 |
| --- | --- |
| 컴퓨터에 저장된 텍스트 파일을 그대로 보는 것<br/>HTML(HyperText Markup Language) | 저장된 내용을 다른 변수로 가공 처리하여 보는 것<br/>PHP(Personal Home Page), ASP(Active Server Page), JSP |

![image](https://user-images.githubusercontent.com/42609725/175790404-53e9ceac-5040-401c-bb80-c10dfe53f955.png)

<br/>

:arrow_forward: 클라이언트-서버

| | |
| --- | --- |
| 클라이언트-서버 모델 기반 | *서버*: 서비스 정보들을 보관하고 이를 제공해주는 컴퓨터<br/>*클라이언트*: 사용자가 서버에서 제공하는 정보를 받는 컴퓨터 |
| 서버 프로그램 | 호스트 컴퓨터에 서버 역할을 수행<br/>아파치(Apache) 또는 IIS 등 웹 서버 프로그램<br/>FTP 서비스의 경우 FTP 서버 프로그램 |
| 클라이언트 프로그램 | 사용자가 서버에 접속하여 서비스 이용<br/>Chrome 같은 웹 브라우저 프로그램/FTP 클라이언트 프로그램 필요

<br/>

:arrow_forward: 종류
| 종류 | 내용 |
| --- | --- |
| Apache web server<br/>HTTP web server | Apache Software Foundation에서 개발한 무료 웹 서버<br/>오픈소스 소프트웨어로써 거의 모든 OS에서 설치 및 사용이 가능 |
| Apache Tomcat | servlet과 JSP script 지원하도록 개발<br/>무료 오픈소스이며 다양한 OS에서 사용 가능 |
| IIS(Internet Information Services)<br/>Windows Server | Microsoft사에서 개발<br/>비교적 고수준의 성능과 보안 제공 |
| Nginx web server | 고성능, 안정성, 간단한 환경 설정과 낮은 리소스 사용<br/>Request를 Thread로 처리하지 않고, 확장성이 있는 이벤트 기반 설계로 예측 가능한 적은 양의 메모리를 사용 |
| Lighttpd | FreeBSD OS와 함께 제공되는 무료 웹 서버<br/>오픈 소스 웹서버로 빠르고 보안성이 있으며 비교적 적은 CPU 파워 사용<br/> Windows, Mac, Linux, Solaris OS에서 사용 가능 |
| Jigsaw | W3C에서 개발<br/>무료 오픈 소스로써 다양한 OS에서 사용 가능<br/>Java로 쓰여졌으며 CGI script와 PHP 프로그램도 실행 가능 |

<br/>

:arrow_forward: 환경 구축 예시
| 서버 | 구성 |
| --- | --- |
| 윈도우 | Windows Server + IIS + ASP + (MS SQL SERVER)<br/>Windows Server + IIS + (PHP module) + PHP + (MySQL)<br/>Windosw Server + IIS + (Tomcat connector) + Tomcat + JSP + (Oracle)<br/>Windows Server + Tomcat + JSP + (Oracle) |
| 리눅스 | Linux Server + Apache + Tomcat + JSP + (MySQL)<br/>Linux Server + Apache + (PHP module) + PHP + (MySQL) |

### :pencil2: 웹 기술


-----
<br/>

### :heavy_check_mark: Q1. AJAX가 무엇인지 예를 들어 설명하시오.

  > #### :star: 기술적 접근보다는 서비스를 예시로 설명.
  > <br/>
  >
  > AJAX는 비동기적인 웹 애플리케이션의 제작을 위해 이용하는 웹 개발 기법으로 주로 회원가입 시 아이디 중복검사나 비밀번호 유효성 검사 등에 사용합니다.<br/>웹 페이지는 화면을 이동할 때 마다 화면의 컨텐츠를 다시 가져와서 표시하는데, 웹 서비스 중에는 화면은 그대로 둔 채로 특정 영역의 데이터를 추가/삭제/변경 등의 기능을 쓸 때 AJAX를 활용합니다.<br/>AJAX를 사용하면 화면 전체를 재로딩함으로 발생하는 트래픽의 증가를 필요한 영역의 적은 데이터만 통신함으로 감소시킬 수 있습니다.

<br/><br/>

### :heavy_check_mark: Q2. 웹 브라우저 검색창에서 키워드를 입력하면 결과가 나오는 과정을 설명하시오.

  > #### :star: 웹 서버의 흐름을 생각하고, 키워드를 입력 받아 웹 서버에서 처리해서 반환하는 과정을 도식화해서 설명.
  > <br/>
  >
  > 웹 브라우저에 있는 검색창에 키워드를 입력하면 웹 사이트의 검색창에 정의된 form의 method(get/post) 방식을 통해 action에 기록된 서버로 검색 키워드를 전송하게 됩니다.<br/>서버는 검색 키워드를 전송받아 이와 관련된 비즈니스 로직을 실행시키고, 그 결과를 HTML로 구성하여 다시 웹 브라우저로 전송하며 웹 브라우저는 서버로부터 받은 HTML의 결과를 화면에 보여줍니다.

<br/>
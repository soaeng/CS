# :triangular_flag_on_post: 하드웨어
<br/>

| 번호 | 내용 | 날짜 |
| --- | --- | --- |
| `001` | 컴퓨터의 논리와 구조 | 2022-06-23 |
| `002` | [프로세서 속도와 심장 박동수](#pushpin-프로세서-속도와-심장-박동수) | 2022-06-23 |
| `003` | [HDD와 SSD의 차이](#pushpin-hdd와-ssd의-차이) | 2022-06-23 |
| `004` | 가로세로 1cm 프로세서 칩 | 2022-06-23 |
| `005` | [50년 넘게 유지된 무어의 법칙](#pushpin-50년-넘게-유지된-무어의-법칙) | 2022-06-23 |
| `006` | [요약(1)](#pushpin-요약1) | 2022-06-23 |
| `007` | [연속과 불연속](#pushpin-연속과-불연속) | 2022-06-25 |
| `008` | 아날로그 정보를 디지털로 바꾸기 | 2022-06-25 |
| `009` | [0과 1의 세계](#pushpin-0과-1의-세계) | 2022-06-25 |
| `010` | 비트 모아 데이터 | 2022-06-25 |
| `011` | [요약(2)](#pushpin-요약2) | 2022-06-25 |
| `012` | 프로세서와 계산기의 다른 점 | |
| `013` | 모형 컴퓨터로 더하기 프로그램 만들기 | |
| `014` | 프로세서는 무조건 빠른 게 좋을까? | |
| `015` | 캐시가 뭔가요 | |
| `016` | 슈퍼컴퓨터부터 사물인터넷까지 | |
| `017` | 요약(3) | |


<br/>

> ### 하드웨어
> : 컴퓨팅에서 형체가 있고 눈에 보이는 부분

<br/>

---
<br/>

### :pushpin: 프로세서 속도와 심장 박동수
:arrow_forward: 폰 노이만 아키텍처

  ![image](https://user-images.githubusercontent.com/42609725/175309575-8117e6d3-0dc1-4752-a4a9-b2e375b8cdd8.png)


:arrow_forward: 컴퓨터 구조

  | 구성 | 내용 |
  | --- | --- |
  | 프로세서 | 산술 연산, 데이터 적재, 다른 구성 요소의 작업을 제어 |
  | 주기억장치<br/>`RAM` | 프로세서가 현재 작업 중인 데이터와 그 데이터로 무엇을 해야 하는지 알려 주는 명령어도 저장<br/>메모리에 다른 명령어를 적재해 프로세서가 다른 계산을 수행하도록 함.<br/>`프로그램 내장식 컴퓨터`: 프로그램의 데이터와 명령어, 운영체제의 명령어 저장<br/>프로세서가 정보에 접근할 때 메모리에 저장된 위치와 무관하게 같은 속도로 접근 가능<br/>휘발성 메모리

<br/><br/>

### :pushpin: HDD와 SSD의 차이
* 보조 기억 장치: 비휘발성 메모리
  
  | 종류 | 내용 |
  | --- | --- |
  | HDD<br/>Hard Disk/Hard Drive | 자기디스크<br/>회전하는 금속 표면에 있는 자성 물질의 미세한 영역이 자성을 띠는 방향을 설정해 정보 저장<br/>비교적 저렴하지만 정보 접근 속도가 느림 |
  | SSD<br/>Solid State Drive | 플래시 메모리 사용(개별 소자에 전하를 유지하는 회로에 정보가 전하 형태로 저장)<br/> 더 빠르고 안정적이며 전력을 덜 사용하지만 가격이 비교적 비쌈 |

<br/><br/>

### :pushpin: 50년 넘게 유지된 무어의 법칙
:arrow_forward: [무어의 법칙](https://www.nnpc.re.kr/bbs/board.php?bo_table=02_01_02&wr_id=70): 기술이 향상됨에 따라 일정한 크기의 집적회로에 들어갈 수 있는 트랜지스터의 수가 1~2년마다 대략 두 배가 된다고 관측(*기하급수적인 증가 양상*)

<br/><br/>

### :pushpin: 요약(1)
> 하드웨어 성능의 향상은 우리가 현실적으로 무엇을 계산할 수 있는지에는 큰 영향을 미치지만, 이론상 계산 가능한 것에는 어떠한 근본적인 변화도 일으키지 않음

<br/><br/>

### :pushpin: 연속과 불연속
:arrow_forward: 컴퓨터가 정보를 표현하는 방식
* 컴퓨터는 디지털 처리 장치기에 **불연속적인 정보를 처리**한다.
* 컴퓨터는 정보를 비트(이진 숫자)로 표현
* 비트는 모여서 더 큰 정보를 표현

<br/>

:arrow_forward: 아날로그와 디지털
* `아날로그`: 연속적으로 변하는 값
* `디지털`: 불연속적으로 변하는 값
  * 디지털 정보는 불필요한 정보를 버리는 방식으로 압축 가능하므로 네트워크 전송 시 효과적
  * 보안과 개인정보 보호를 위해 암호화
  * 다른 데이터와 병합
  * 이식성
  * 확장성

<br/><br/>

### :pushpin: 0과 1의 세계
:arrow_forward: 비트(bit) - 이진 숫자(binary digit)
* 0 또는 1 중 하나의 값을 사용
* 두 개의 값 중 하나를 선택하는 정보라면 1bit로 표현 가능
* 2의 거듭제곱으로 제공하는 정보의 양 증가
* 2의 10승 = 1024

### :pushpin: 요약(2)
> 상대적인 단순성 때문에 컴퓨터에서는 이진수 사용. 


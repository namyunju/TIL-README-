# TIL-README-
TIL (add a README file)
---
<details><summary>SSAFY 생활</summary>

9~11 라이브 강의
11~12 개인 복습(학습 내용 나의 언어로 정리)
12~13 함께 복습
점심
14~ 복습 및 온라인 실습 git.project 

온라인 실습
문제 들어가서 my gitlab 하고 주소 복사. 내 파일 bash 열어서 git clone 컨트롤 인서트 해서 로컬에 가져옴. 
코드 작성하고 저장. 커밋 add -m 한 후에 push. 온라인 실습실 제출까지 꼭꼭


시험은 온라인 교재에서 많이 출제됨 최소 3회독 이상

</details>


<details><summary>개발 첫 걸음_ 학습 안내</summary>

# AI 시대 공부
처음 프로그래밍 배울 때 완벽을 추구하면 길을 잃기 쉽다. 
제일 중요한 것은 ``문제 해결 능력``
Ai 시대 빠른 속도 새로운 기술. 

기초 개념 정확히 잡으면서 계속해서 실습과 프로젝트로 코딩 감각을 익히는 과정을 해 나가야 함!!

과거처럼 모든 문법 외우고 코드를 빨리 짜는 능력? 상당 부분 AI가 대신해줄 수 있음. 

`AI라는 강력한 도구를 지휘하는 문제 해결 전문가`

경쟁력은 무엇을 만들고 싶은가? 본질적인 질문 던지는 능력.

AI에게 정확한 요구사항 전달, 결과물을 비판적으로 검증하는 능력.

이는 실습과 프로젝트를 통해 아이디어를 실현하는 과정에서 단련됨.

**코드를 통해 아이디어를 실현하고, 실용적인 결과물을 만드는 과정 을 즐기고 습관화 할 것**
AI와 협업하는 습관을 기르며 최선을 다한다면, 꾸준히 학습하고 경험을 쌓는다면, 대체 불가능한 개발자로 성장할 것.




# 학습 방법
**문제해결의 큰 그림을 그리고 핵심역량을 기르는 데 집중하자.**

어려운 개념은 개념만 이해, 인지하고 이후 심화적인 것은 필요 시 전문 도구를 사용하면 됨.

기초단계에서 메모리, 성능 최적화 얽매이지 말고 개발 경험을 쌓자.
작은 기능을 직접 완성해보는 실질적인 개발 경험이 쌓이면 성능에 대한 감각은 자연스럽게 따라옴.

AI 이용.
의도를 파악해 변수명을 다듬고 작동 이유에 대한 주석을 달며 읽기 쉬운 코드를 만들기.

디버깅 역량
코드가 원하는 대로 동작 않는 것이 개발의 진짜 시작.

AI에게 에러와 코드 보여주고 왜 발생했는지, 어떻게 해결하는지 물어보기. 구글링과 공식 문서 읽기
항상 비판적으로 검토하고 테스트하며 더 나은 방법을 생각하기.

무엇을 모르는지 파악하고 **AI에게 명확하게 질문하여 답을 얻어내는 능력**

결국엔 뭐다? 어떤 문제를 해결하고 무엇을 만들어낼 수 있는가.
각종 언어들은 이를 위한 도구.


</details>


<details><summary>2025/07/16</summary>

배운 내용:
CLI 기초문법과  martdown, git 사용법

CLI: 명령어로 사용자와 컴퓨터가 상호작용 하는 방식 command line interface

기초문법

. 현재 디렉토리
.. 상위 디렉토리
touch, mkdir, ls, cd, start, rm, pwd


CLI에서 가장 중요한 것! 경로

루트 디렉토리 / 
홈 디렉토리 ~


Markdown: 일반 텍스트로 문서를 작성하는 방법! 텍스트와 코드를 작성해 문서화.

마크다운의 여러가지 기능!

# 개발자로 성장하기
이런 거 
- 또 이런 거
**이런 것도** 되고
*이런 것* 도 되고 
---
이것도! 신기하죠?

1. 순서가
   1. 있는
        1. 리스트?

```python
print('hello')
```
이런 것도 `를 이용하여 표현 가능.쩌거 3개로 묶어주기

[이런 것도](ㅋ)
누르면 안됨
![이미지도](ㅋ) 안되긴 해
~~취소선~~
물결로 만든 취소선!

더 알고 싶은 건 마크다운 가이드로!


<details><summary>git 이용법</summary>


Git이란? 분산 버전관리 시스템

버전관리란 변화를 기록하고 추적하는 것.

git은 파일의 변경 이력을 모두 기록한다. 누가 언제 무엇을 변경했는지 알 수 있고 이전 버전으로 돌아갈 수도 있고 실수로 잘못 변경했을 때 되돌리기도 쉽다! 뭐 게임 잘못 업데이트해서 버그 생기면 과거 특정 시점의 상태를 복원할 수가 있다!!!

분산형 시스템이라 중앙 서버 없이 작업이 가능하다. 오프라인상태에서도!!
협업도!
배포와 백업에도 좋다.

---

git의 3영역

`working directory, staging area, repository`

작업디렉토리는 git 리포지토리 파일이 실제로 저장된 위치로 파일을 편집, 추가, 삭제하는 작업을 진행함. git은 이 파일들이 변경되었는지 여부를 **추적**하지만!!! 이 시점에서 Git이 그 변경을 **관리**하지는 않는다. 

변경 사항을 Git에 반영하기 위해서는?? Staging area 즉 스테이징 영역으로 이동시켜야 한다. 그것은 git add 파일명 또는 . 을 통해. 그러니까 git add는 git아 변경 사항 추가해줘~~ 하는 거임

Staging 영역은 Git 파일이 다음 커밋을 준비하는 곳! commit은 버전이라고 생각하면 됨. 스테이징 영역에 파일을 add 하면 git은 해당 파일을 추적하고 그 상태를 커밋할 준비가 된 상태로 만든다. 스테이징 영역에 추가된 파일은 커밋될 때만 실제로 버전관리가 이루어짐.

git status로 파일들의 위치 알 수 있음. 스테이징 영역에 있구나!

Repository 리포지토리 바로바로 git이 파일의 버전 이력을 관리하는 곳!!! 로컬 리포지토리는 작업 중인 프로젝트의 모든 버전과 변경 사항을 기록. git commit 명령 사용하여 파일을 스테이징 영역에서 로컬 리포지토리로 커밋하면 !! git이 변경 사항을 기록하고 새로운 버전으로 저장한다. 레포지토리에는 커밋 내역과 브랜치 정보가 포함되며 모든 변경 사항은 이곳에서 관리됨.
git commit -m "커밋 내역" 이렇게 치면 git은 변경 사항을 로컬 리포지토리에 저장하고 버전 히스토리에 기록한다. git log로 확인


예시 워크플로우

작업 디렉토리에서 파일을 수정한다. >> git add 파일명 으로 변경사항을 스테이징 영역에 추가하고 >> git commit -m "커밋명" 으로 레포지토리에 커밋하고! >> 리포지토리에 변경 사항을 원격 서버로 푸시하려면 git push origin main !! 
</details>


</details>


<details><summary>2025/07/17</summary>
   오늘 배운 것

Git 로컬과 원격 저장소 왔다갔다 

github 쓰는 방법

나 지금 수정하고 있잖아~~!!
저장을 안해서였다...
commit 수정 방법??

---
</details>

<details><summary> 2025/07/21 </summary>

**프로그래밍의 의미와 Python 소개 및 Data type 특징**

## 프로그래밍
프로그램: 어떤 문제를 해결하기 위한 명령어 집합 
프로그래밍의 핵심은 새 연산을 정의하고 조합해 유용한 작업을 수행하는 것!


파이썬?! 타언어에 비해 쉽고 간결한 문법
풍부한 커뮤니티와 광범위한 응용 분야(웹 개발, 데이터분석, 인공지능 등)


왜 ai와 머신러닝 개발에 파이썬을 쓸까?
여러 라이브러리 도구들이 모두 파이썬으로 제공됨.(왜? 그냥 첨 만든 사람이 파이썬으로 했나?)

파이썬 인터프리터가 사용자의 명령을 기계어로 바꿔줌

파이썬 인터프리터

1. 인간이 파이썬 프로그램 작성
2. 파이썬 인터프리터가 코드를 한 줄씩 읽고 문법 오류 확인. 없으면 바이트 코드(운영 체제가 이해하는 언어)로 변환하고 실행

사용법 2가지 
- shell 프로그램으로 한 번에 한 명령어 입력하여 실행
터미널에서 python -i 하면 파이썬 인터프리터 환경이 실행됨
근데 이렇게 잘 안 함.
>>>

- 확장자가 .py인 파일에 작성된 파이썬 프로그램 실행
파이썬 파일 vs code 터미널에 아래와 같이 입력하여 실행
$ python saple.py

  
# 표현식과 값
- 표현식: 하나의 '값'으로 평가될 수 있는 모든 코드
표현식 예시 : 3+5 / x>10 / 5*4

평가: 표현식을 계산하여 그 결과인 값을 만들어내는 과정

- 값: 표현식이 평가된 결과. 더이상 계산되거나 평가될 수 없는 프로그램의 가장 기본적 데이터
값 예시 : 8, True, "안녕하세요"

주의: 모든 값은 가장 단순한 형태의 표현식. 모든 표현식이 값은 아님.
3+5는 표현식. 자체로는 값이 아니고 평가를 거쳐야 값 8이 됨.

표현식이 평가를 거치면 값
값이 평가를 거치면 값

값이 표현식에 포함됨. 값 < 표현식


# 변수와 메모리

변수: 값을 재사용하기 위해 그 값에 붙여주는 고유 이름(값에 붙여주는 거지 표현식에 붙이는 게 아님 a = 3+5 라면, a에 8이라는 값을 할당한거지 3+5라는 표현식을 할당한 것이 아님)

a = b+1
b=2
print(a) 에러 뜸. 순서

변수 할당: 표현식이 만들어 낸 값에 이름을 붙이는 과정(연결)

할당 연산자 = : 오른쪽 표현식의 평가 결과 값을 왼쪽 변수에 저장

할당문: degrees = 36.5

변수명 규칙: 알파벳, _, 숫자로 구성. 숫자로 시작 불가. 대소문자 구분. 

파이썬의 내부예약어로는 변수 이용 불가능. True False None and as assert async 


- 변수, 값, 메모리

   우리가 변수 만들면 (a = 3) 그 '값'이 메모리 어딘가에 저장.
  변수는 그 메모리 위치 가리키는 이름표 역할. 변수는 메모리 주소 가지지 않음.
  변수는 객체를 가리키는 이름!!
  변수의 메모리 주소가 아니라 값의 메모리 주소임

그래서 여러 변수에 같은 값을 할당하는 경우 그 변수들이 가리키는 객체는 동일하고 메모리 주소도 동일함. 변수에 다른 값을 재할당하면 다른 값을 가리키게 되므로 메모리 주소도 바뀜

  메모리의 모든 위치에는 그 위치를 고유하게 식별하는 메모리 주소가 존재.(메모리주소: 컴퓨터가 특정 데이터값 정확히 찾기 위해 사용하는 기계적 숫자 주소)  

**객체**
파이썬의 모든 데이터가 객체
숫자 문자열 리스트 함수 모두 객체

객체는 3가지 정보를 가짐. **고유 ID(메모리주소) Type(타입) Value(값)**
값 타입 주소 3 개 정보를 묶은 것을 객체 object라 부름.
id(a) type(a) 


ex) a = 3 하면 3이라는 객체(메모리 주소, 타입: 정수, 값:3) 가 메모리에 만들어짐. 
a는 그 객체를 가리킴. b = a 라 하면 b도 같은 객체 3을 가리키게 됨.

그래서 a, b 메모리 주소 같아짐. 하나를 바꾸면 둘 다 같이 바뀜

<img width="321" height="387" alt="image" src="https://github.com/user-attachments/assets/972a18c6-a3a0-483c-8dc7-fa5cb6073c4d" />

<img width="357" height="399" alt="image" src="https://github.com/user-attachments/assets/de43150d-d438-4709-a4c1-e7fcab14fb6a" />

변수는 특정 객체를 가리키는 이름표. 
변수는 메모리주소를 가지지 않는다.참조할 뿐
변수는 한 마디로 '객체를 가리키는 이름'


할당문 variable = expression

- 할당문 동작 순서
오른쪽 표현식 평가. 계산하여 하나의 결과값(객체)를 만듦. > 왼쪽 변수명 확인. 새로운 이름표 만들거니 기존 거 이용 > 변수명과 결과값 연결!!(참조). 변수가 이전에 다른 객체 가리키고 있었다면 그 연결 끊어지고 새로운 객체와의 연결만 남음 (재할당)



|용어|핵심 정의|비유(주소록)|
|---------|------|------|
|객체 object|데이터(값 타입 행동)의 실체|'김철수'라는 실제 사람|
|메모리 주소|객체가 저장된 고유한 위치|김철수의 실제 집 주소|
|변수 variable|객체를 가리키는 이름표|주소록에 저장된 '내친구 김철수'라는 이름|



# 데이터 타입

아까 객체는 고유id 메모리 주소, 타입, 값 의 묶음이라 했죠?
데이터 타입은 값의 종류와 적용 가능한 행동의 묶음입니다.

타입: 변수나 값이 가질 수 있는 데이터의 종류

타입의 구성요소: 값(피연산자)과 값에 적용 가능한 연산자. 이 두 가지로 구분할 수 있음. 

값은 숫자일수도 글자일 수도 소수일 수도 있음

중요한 이유: 값의 종류와 그 값으로 할 수 있는 연산을 결정하기 때문. 즉, 타입마다 가능한 기능과 연산이 다름.

data type: 값의 종류와 그 값으로 할 수 있는 동작(연산)을 결정하는 속성


데이터 타입의 5분류: numeric types / text sequence(str) / sequence type(list tuple range) / non sequece type ( set, dict) / 기타 (boolean none functions)

정수 int 
실수 float 소수점까지. 
지수표현법 1,230,000,000은 1.23 * 10^9 인데 이걸 1.23e9라고 표현함.
0.00314는 3.14 * 10^-3 이라서 3.14e-3이라 씀 e E 상관없음.
<img width="437" height="364" alt="image" src="https://github.com/user-attachments/assets/a51cdb69-6f81-463e-8f8f-84b1f35a7757" />


숫자형 타입의 행동은 산술 연산!
<img width="312" height="120" alt="image" src="https://github.com/user-attachments/assets/c580aaba-8465-4a9f-b133-ca8b4bcb1d9b" />
<img width="310" height="108" alt="image" src="https://github.com/user-attachments/assets/fe3c42c4-0f3e-4c7e-acde-d0b43f4fc1ea" />

연산자 우선순위는 동일 ** 다음 -(음수부호) . () 사용 가능.

    -2**4 = -16 = -(2**4)


시퀀스 타입: 여러 데이터가 정해진 `순서`대로 일렬로 `나열`하여 저장하는 자료형 
대표 시퀀스 타입: str, list, tuple, range

순서가 있으므로 인덱스가 존재. 0번부터. 인덱스를 통해 데이터에 바로 접근 가능 

index: 시퀀스 자료형에서 각 값의 위치를 식별하기 위해 부여된 고유한 번호 (0번부터)

시퀀스타입 여러가지인데 공통 특징 5가지있음.
순서대로 저장(정렬된 것은 아님)/인덱싱(값마다 고유 번호 있어서 특정 위치 값 선택 수정 가능)/슬라이싱(원하는 부분 값만 잘라서 사용)/길이(값의 개수 len() 함수 )/iteration(반복문으로 각 값 하나씩 순서대로 꺼내서 사용 가능)

len 은 전체 길이 (개수)알려줌. 
인덱스는 0부터 len-1 까지. 길이 넘어서는 인덱스 입력 시 에러뜸



시퀀스 타입 중 문자열str
```python

my_data = 'Hello'

my_data[1] = 'e'
my_data[1:4] = 'ell'


```
len은 5임. 인덱스는 0부터 4까지 존재
[1:4] 하면 1번부터 3번까지 해당됨. 항상 뒤에 오는 인덱스는 제외하고 그 이전까지만.

문자열 str : 문자들 `순서` 있고 `변경 불가능`한 시퀀스 자료형

`escape sequence`
\ 역슬래시와 문자 조합 특별한 기능
\n 줄바꿈 \t 탭 (띄우기) \\ 백슬래시 하나 \' 작은 따옴표 \" 큰 따옴표 \b는 앞에 지움

여러 줄 작성 시 ''' 또는 """ 이용 ('하나만 쓰면 한 줄만 인식해서 에러뜸)



# f-string 아주 중요!

문자열 내에 변수나 표현식의 결과를 쉽게 삽입하는 방법.
문자열 시작 전에 f 붙이고 삽입할 부분을 {} 로 감싸줌. 

```python
name= '홍길동'
age=25

greeting = f'안녕하세요, 제 이름은 {name}이고 나이는 {age}살입니다.'

```
안녕하세요, 제 이름은 홍길동이고 나이는 25살입니다.


<img width="299" height="173" alt="image" src="https://github.com/user-attachments/assets/4fc74cb7-bb0e-4208-b27a-188ade47daa6" />

f-string 다양한 기능 있음. 심화 사용법 알아보기





index: 시퀀스 자료형 각 값의 위치를 식별하기 위해 부여된 고유 번호. 0부터 시작 왜? 거리 개념임. 시작점으로부터 떨어진 거리. 
음수 인덱스 지원. -1은 맨 마지막 값. 

slicing: 시퀀스 일부분 잘라내어 `새로운 시퀀스 생성`
슬라이싱 사용법 대괄호 [] 안에 시작 위치, 끝 위치, 간격 을 콜론:으로 구분하여 지정
my_sequence[start:stop:step]
<img width="392" height="327" alt="image" src="https://github.com/user-attachments/assets/e0450cc0-7328-491c-8bce-1073db4ee270" />

start 시작인덱스(포함)
stop 끝 인덱스(포함x)
step 건너뛰는 간격 
상황따라 생략 가능


my_str[2:4] 하면 2,3 자리 나오고 4는 포함 안됨.

왜 끝에 값은 빠질까???
시작 값은 0 n번 반복 시 실제로 마지막 시행은 n-1번째가 됨. 즉, 3번 반복 시 0,1,2 가 시행됨. 그래서 마지막 수 앞에서 멈춤.
너무 헷갈린다면 문자열 사이를  index로 생각.


여러가지 해보니까 my_str[7]처럼 아예 벗어난 인덱스 주면 error 뜨는데 [7:9] 나 [9:7] 같은 거 넣으면 error 안 뜨고 그냥 값이 안 나옴. [::-1] 은 역순


`문자열의 불변성`

문자열은 순서가 있고 변경이 불가능한 시퀀스형 자료!!!
(리스트는 변경 가능)
my_str[1] = 'a' 와 같이 할당하려하면 error
type error 'str' object does not support item assignment 

변경은 불가능. 재할당하거나 새로운 문자열을 생성하는 수밖에


<details><summary>참고</summary>

진법 표현 접두사 prefix
0b 0o 0x

2진수 print(0b10) >>> 2 (2진수 10은 10진수로 2)
8진수 print(0o30) >>> 24 (8진수 30은 24)
16진수 print(0x10) >>> 16 (16진수 10은 16)

<img width="332" height="384" alt="image" src="https://github.com/user-attachments/assets/6f3a3543-9a98-486e-bfb8-43e7830d5d76" />


실수의 함정, 부동소수점 오차

result = 0.1 + 0.2 

print(result == 0.3) False

print(result) 0.300000000004

왜?
컴퓨터의 실수 처리 방식.
부동소수점(반올림)오차


컴퓨터는 2진법을 사용. 무한 소수의 발생과 근삿값 저장.10진수 소수 중 일부 2진수로 바꾸면 무한 소수 됨. 

예를 들어 0.1 을 2진수로 바꾸면 무한 소수가 됨. 0.0001100110011 ...

메모리 유한하므로 근삿값으로 잘라서 저장함. 근사치로 인해 오차 발생.


> 해결책

decimal 모듈 사용해 부동소수점 연산의 정확성을 보장 
실수를 2진수로 변환하지 않고 10진수 자체로 정확하게 연산할 수 있게 해줌.
소수 계산할 때 조심하기

a = Decial('3.2')


# 표현식과 문장

표현식은 아까 했죠? 
평가를 거쳐 값이 되는 것을 표현식이라고 한다고. 3+5 True 등

표현식이 아닌 거는 뭐가 있냐? 바로 그게 문장! 

표현식이 값을 만들어내는 코드조각, 문장은 동작을 수행하는 코드 조각

print(10) 은 값을 반환하는 게 아니라 출력하는 동작을 함. 따라서 문장. (print는 반환값이 None)

max(2,3) 은 값을 반환하므로 표현식

할당문 조건문 반복문 등!! 문장은 statement 특정 동작을 지시하는 실행 가능 코드 최소단위. 문장은 완결된 하나의 명령 

예시: x = 100 / def my_function() / pass 등


구분: 코드 실행 시 하나의 값이 남는다면 표현식, 안 남는다면 문장. 
10+20 : 표현식
name = '홍길동' : 문장(변수에 지시했을 뿐 값이 남지 않음)

관계도 : 문장 == 요리법       표현식 == 재료

표현식 사용해서 문장 만들 수 있고 표현식 하나가 문장이 되기도?

total_price = 5000 + 1000  : 할당문 (문장)

뜯어보면

5000 + 1000 : 표현식 (값 6500을 만들어냄)

total_price = : 표현식이 만든 값을 변수에 할당하라고 지시하는 문장

대부분 문장은 표현식을 포함하여 동작

Style Guide 코드의 일관성과 가독성을 향상시키기 위한 규칙과 권장 사항들
대표적으로 PEP 8

직관적인 이름, 공백 스페이스 4칸 or Tab
한 줄 길이 79자, 길면 줄 바꿈 
문자와 밑줄로 작성, 함수 정의 클래스 정의 등 블록 사이에는 빈 줄을 추가

age=10 말고 age = 10

주석:
샾 사용 여러줄은 """ 또는 묶어서 한 방에 컨트롤 슬래쉬

복잡한 코드 python tutor 코드 한 줄씩 어떻게 실행되는지 눈으로 보여주는 시각화 도구



터미널에 ls 쳐서 내가 실행하고 싶은 파이썬 파일이 존재하는지 확인하고 실행하기
python 파일이름 하면 내가 원하는 파이썬 파일 실행됨.

double에 2*10 값을 저장한 것,
값이 저장되는 것이지 표현식을 저장하는 것이 아님.
좀 중요함 헷갈리는 부분. double에 20이 저장되는 것이지 2*num 이 저장되는 것이 아니다잉


16진수
0부터 9까지 이용 후 a부터 f까지 감 우왕~~굉장히 10진법적인 사고



</details>
</details>


<details><summary>2025/7/22</summary>

**여러 데이터 타입과 연산자**

다양한 데이터 구조와 연산자를 활용하여 장바구니를 직접 만들고 관리할 수 있다.


복습: 시퀀스 자료형 시퀀스의 특징 5가지
시퀀스 자료형이란, 여러 개의 값을 `순서`대로 저장하고 각 요소를 `인덱스`를 통해 접근할 수 있는 자료형.
str, list, tuple이 있음. (dict와 set은 시퀀스 자료형 아님. 순서 없고 인덱스로 접근 불가)

특징 5가지: 순서 있음, 인덱싱 가능 a[2], 슬라이싱 가능 a[1:3], 반복 가능, 길이 확인 가능

(추가: 문자열뿐만 아니라 정수형, 실수형 등도 불변. a = 10 에서 0을 1로 인덱싱해서 바꾸는 것 불가능. 재할당하는 수밖에)


# 리스트

- 여러 개의 값을 `순서`대로 저장하는,`변경 가능한``시퀀스 자료형` mutable
- 시퀀스이므로 인덱싱 슬라이싱 길이 모두 가능
- 대괄호[] 안에 값들을 쉼표 , 로 구분
- 숫자 문자열 다른 리스트까지 모든 종류 데이터 담을 수 있다.
- 값을 추가 수정 삭제 등 자유롭게 변경 가능 
- 중첩nested 리스트 : 다른 리스트를 값으로 가진 리스트 my_list[4][2][3]

중첩: 어떤 자료 구조 안에 같은 종류의 자료 구조가 포함된 형태
(재귀함수같은)
 
 
가변성: 생성된 후 그 내용을 변경할 수 있는 성질.
변경: 수정 추가 삭제 
문자열의 불변성과 정반대되는 중요한 특징.

1. 인덱싱으로 값 수정하기
2. 슬라이싱으로 여러 값 한번에 바꾸기
my_list = [1,2,3,4,5]
my_list[2:4] = ['three', 'four']
print(my_list) [1,2,'three,'four',5]
list는 가장 많이 활용하게 될 data type 중 하나

[2:4]로 하면 2,3  요소 없어지고 그 자리에 들어가는 새로운 요소 개수 제한 없음.

<img width="496" height="246" alt="image" src="https://github.com/user-attachments/assets/73300151-675f-498f-a1b8-4dd065878f3c" />
<img width="639" height="398" alt="image" src="https://github.com/user-attachments/assets/a40456bb-cc2e-4501-b7df-0759aff43c8d" />
<img width="394" height="215" alt="image" src="https://github.com/user-attachments/assets/063b9fad-b964-4ffb-af10-c07969e5fca3" />

슬라이싱 할당에서 오른쪽에는 반드시 반복가능한 iterable 객체가 와야 함. 그래서 정수 불가능.

하나씩 쪼개서 할당함. 

반복 불가능: int float boolean Nonetype complex


# 튜플

- 여러 개의 값을 `순서`대로 저장, `변경 불가능`한 시퀀스 자료형
- 소괄호() 이용, 쉼표 , 로 구분
- 리스트처럼 모든 종류 데이터 담을 수 있음
- 리스트와 유사하나, 한 번 만들어지면 수정 불가능. `불변성`
- 시퀀스이기 때문에 순서, 인덱싱, 슬라이싱, 길이 확인, 반복 이용 가능   
  특징
  - 요소가 하나일 때 쉼표 , 이용 my_tuple = (1, ) trailing comma 후행쉼표라고 함.
  - 물론 빈 튜플도 가능 my_tuple = ()
  - 소괄호 없이 만들 수 있음. my_tuple = 1, 'hello', 3.14
<img width="401" height="123" alt="image" src="https://github.com/user-attachments/assets/5c732366-7e6b-45c3-90b7-6a953aedd84a" />
후행 쉼표 없으면 int가 되네<img width="420" height="238" alt="image" src="https://github.com/user-attachments/assets/24a4f05f-b769-40cc-8399-9e423bb49680" />


튜플은 언제 쓰냐?
튜플이 불변 자료형인 이유는?
튜플의 불변 특성을 사용하여 내부 동작과 안전한 데이터 전달에 사용.
다중 할당, 값 교환, 함수 다중 반환 등
개발자가 직접적으로 사용하기보다는 내부적으로 처리될 때 사용됨

튜플은 데이터의 안정성과 무결성을 보장하기 때문에 리스트와 구별됨. 내부동작에서 사용
실제 문제 풀 때 쓰는 경우 거의 없음.

<img width="508" height="284" alt="image" src="https://github.com/user-attachments/assets/213da17c-9bd7-482c-96cc-809bd42c76bc" />




```python
#다중할당
x, y = 10, 20
#실제 내부 동작
(x, y) = (10, 20)

#값 교환
x, y = 1, 2
x, y = y, x

#실제 내부 동작
temp = (y, x) # 튜플 생성
x, y = temp # 튜플 풀어냄
print(x, y) # 2 1

```


# range

`연속된 정수 시퀀스` `생성`하는 `변경 불가능`한 자료형

(변경 가능한 자료형은 아직 리스트밖에 없노! 문자열, 튜플, range 다 불변)
- range는 주로 문에서 사용. 특정 횟수만큼 딱 
- 시작, 끝, 간격 규칙만 기억. 메모리 효율적
- range() 는 1,2,3 개까지의 매개변수를 가질 수 있음.
  - range(stop)
  - range(start, stop)
  - range(start, stop, step)

```python
# 매개변수 하나일 때. stop으로 인식. start는 0, step은 1이 기본값으로 설정
my_range_1 = range(5)

print(my_range_1) # range(0, 5)

print(list(my_range_1)) # [0, 1, 2, 3, 4] 리스트로 형 변

# 매개변수 두 개
my_range_2 = range(1,10)

# 매개변수 세 개
my_range_3 = range(5, 0, -1)

print(list(my_range_3)) # [5, 4, 3, 2, 1]


```
- range에서 모든 숫자 메모리 저장하는 게 아니라 시작, 끝, 간격이라는 규칙만 기억하여 메모리 효율적
- range는 list로 `형 변환` 시 내부 값을 확인 가능. 실제 사용할 때는 형 변환하지 않고 문에 사용

```python
for i in range(1,10,2):
   print(i)   # 1, 3, 5, 7, 9
```

step 규칙
step은 시퀀스의 간격과 방향을 결정
error가 나지는 않음. step의 부호에 따라 start와 stop의 대소관계 생각.

항상 스탑 값 앞까지! stop 값은 시퀀스에 포함될 수 없음


# dict

오늘의 수업 중 젤 중요한 것 두 가지 꼽으라면 list와 dict

**딕셔너리: key와 value 쌍으로 이루어진, 순서와 중복이 없는 변경 가능한 자료형.(비시퀀스)**

순서가 없다?! >> 인덱스가 없다.
인덱스 없이 어떻게 접근해? >> key로 접근!

- 중괄호 {} 이용. 쉼표, 로 구분
- 값 1개는 키와 값이 쌍으로 이루어져있음
- my_dict = {'key': 'value'} # 한 쌍
  
- key: 값을 식별하기 위한 고유한 이름표. 중복 불가(순서가 없는 대신 고유한 키로 구분).
  변경 불가능한 자료형만 사용 가능. (str, int, float, tuple 가능, list, dict 불가능)
  
- value: 키에 해당하는 실제 데이터. '문자열', 12, [l, i, s, t] 모두 가능

- key로 value 찾기 가능, 역은 불가능. key는 고유하지만. value는 여러 번 나와도 됨.

- key가 두 번 이상 나온다면? 뒤에 나온 것 기준으로 하나만 나옴.

dict = {'apple': 500, 'apple': 300} 
print(dict['apple']) # 300


순서가 없는 자료형. 비시퀀스. key를 통해 접근

print(my_dict_1[key]) 하면 value가 나옴, 존재하지 않는 key 쓰면 error

딕셔너리 언제 이용하냐?

데이터에 순서 필요 없고 데이터에 key 붙여 관리하고 싶을때 이용. 인적 정보나 캐릭터 능력치 


# set
---
`순서와 중복이 없는` `변경 가능`한 자료형. 비시퀀스(인덱싱, 슬라이싱 사용 불가. 근데 len은 사용 가능.)

두 가지 핵심: 중복 허용 X / 순서가 없음! (인덱싱 슬라이싱 불가능)

- 중괄호{} 이용, 쉼표 , 로 구분.
- 딕셔너리도 중괄호 {} 이용! >> 공집합은 {}로 표현 못함. 딕셔너리니까! set() 으로
- my_set_1 = set() 라고 표현함. my_set_2 = {1, 1, 2} #print(my_set_2) {1, 2}
- 원소 동일하면 하나만 나옴.(중복 불가) 순서 없으므로 인덱싱 불가
- 합집합 | (shift 백슬래쉬), 차집합 -, 교집합 &
- 중복 제거하고 싶을 때 사용 가능
- 잘 사용 안하긴 함. 특수 상황에서 사용


# Other types
---
None: 값이 없음을 표현하는 특별한 데이터 타입. 숫자 0이나 빈 문자열 '' 과는 다름!! 값이 존재하지 않음, 아직 정해지지 않음 이라는 상태를 나타냄.
대소문자 주의. None 이다.

Boolean: 참과 거짓 두 가지 값만 가지는 데이터 타입. 프로그램의 흐름을 제어하는 조건문에서 True와 False를 판단
주로 조건 문과 함께 사용됨.
비교 논리 연산의 평가 결과



# Collection
---
여러 개의 값을 하나로 묶어 관리하는 자료형들을 `통칭`하는 말
str, list, tuple, range, set, dict 데이터 타입 모두 Collection에 분류.

|컬렉션명 | 변경 가능 여부(가변성, 불변성) | 순서 존재 여부(인덱싱 가능 여부)|
|---|---|---|
|str |X|O|
|list|O|O|
|tuple|X|O|
|dict|O|X|
|set|O|X|
|range|X|O|


# 형변환
---
한 데이터 타입을 다른 데이터 타입으로 변환하는 과정.


암시적 형변환과 명시적 형변환

암시적 형변환: 파이썬이 연산 중에 자동으로 데이터 타입을 변환하는 것

데이터 손실 막으려고 더 정밀한 타입으로. 더 안전한 쪽으로 파이썬이 자동 처리

불리언과 뉴머릭 타입에서만 가능함.
숫자형 자료 더 큰 범위로, boolean과 수

ex) print(3 + 5.0) # 8.0
   print(True + 3) # 4
   print(True + False) # 1

명시적 형변환: 개발자가 변환하고 싶은 타입을 직접 함수로 지정하여 변환하는 것.
서로 다른 타입의 데이터를 호환되도록 맞추는 과정.
해외에서 어댑터 끼우는 느낌. 

int("123") 결과 123
str(100) 결과 "100"
list("abc") 결과 ['a', 'b', 'c']
set([1, 2, 2]) 결과 {1,2}
<img width="373" height="160" alt="image" src="https://github.com/user-attachments/assets/0bfee477-15fe-469d-b8f8-647d2c25cfe9" />

항상 되는가?

str -> int 형식에 맞는 숫자만 가능

print(int('1')) # 1 '1' 문자열을 정수로 형 변환.

print(int('3.5')) # '3.5'는 실수형태의 문자열이므로 error 뜸.

print(float('3.5')) # 3.5 '3.5'라는 문자열을 실수로 형 변환.

print(int(1.9)) # 1 실수를 정수형으로 형 변환.

int -> str 모두 가능

print(str(2) + '등') # 2등

그 무엇도 range와 dict으로 형 변환 불가능함.


# 연산자
---
산술연산자, 복합연산자, 비교연산자, 논리연산자, 단축 평가, 멤버십연산자, 시퀀스형 연산자 그리 연산자 우선순위


복합연산자: 연산과 할당이 함께 이뤄짐.

+= -= *= /= //= %= **=  알 것 같기도~  x **= 3 : x에 x의 3승을 할당해라

비교 연산자

True False 로 반환

ㅡ=, ==, !=, is, is not

is 연산자는 단순 값 비교가 아닌 객체를 비교. 메모리 주소가 같은지를 확인 식별성

is: identity operator 정체성   ==: equality operator 값

is 연산자는 싱글턴 객체 비교에 사용

프로그램 전체에서 단 하나의 객체만 생성되어 재사용되는 특별한 객체. 싱글턴 객체: None True False


<img width="318" height="399" alt="image" src="https://github.com/user-attachments/assets/57e6cced-8a79-4895-8597-1d1a464b88bc" />

b=a 
print(a is b) True

논리 연산자
and or not


단축 평가: 논리 연산 두 번째 피연산자 평가하지 않고 결과를 결정하는 동작

똑똑한 게으름?!: 결과가 정해졌다면 뒤에 코드까지 확인하지 않음. 이렇게 결과가 확정되는 순간 평가를 '단축'하고 넘어간다고 해서 '단축 평가' 라고 부름.

거짓으로 취급되는 값들: False, 숫자 0, 빈 문자열 "", 빈 리스트 [], None 등 
참으로 취급되는 값들: True, 1, -10, "hello", [1,2] 등 내용이 있는 값

and 연산자 하나라도 거짓이면 거짓. 쭉 가다가 처음 만나는 거짓을 바로 반환. 모두 참이면 마지막 참 반환

or 연산자 하나라도 참이면 참. 끝까지 갔는데 모두 거짓이면 맨 마지막 거짓값을 반환

단축 평가 >> 코드 실행 최적화하고 불필요한 연산 피함, 코드 흐름 제어 오류 방지 간결 코드 


멤버십 연산자: in, not in 
print('h' in word)  
왼쪽이 요소 오른쪽이 컬렉
결과값: True, False


시퀀스형 연산자: + *
+ * 가 시퀀스자료형(문자열, 리스트, 튜플)에서 결합,  연산자로 쓰임.


trailing comma(후행 쉼표)
컬렉션의 마지막 요소 뒤에 붙는 쉼표
앞에 하나의 요소로 구성된 튜플에서 필수였음. tuple = (1,)
그 외에는 `선택 사항`


기본규칙
각 요소 별도 주루 작성하고 콤마 추가 닫는 괄호도 새로운 줄

딕셔너리에서 잘 사용됨. 가독성 측면에서

```python
item = [
   'item1',
   'item2',
   'item3',
]

config = {
   'host': 'localhost',
   'port': 8080,
   'debug': True,
}


```

각 요소 별도 줄에 작성. 마지막 요소 뒤에 trailing comma 추가, 닫는 괄호는 새로운 줄에 배치.
그냥 한 로 쭉 쓸 때는 trailing comma 쓰지 않음.

`문제 풀이
리스트 [1:4]면 그 앞에까지 
딕셔너리는 {'키': '값'}
역순[::-1]
set는 순서 없고, 중복 허용하지 않음
딕셔너리는 value 바꿀 수 있음.

</details>

<details><summary>추가학습</summary>

<details><summary>얕은 복사와 깊은 복사</summary>

python tutor 을 이용한 시각화

메모리 위치


backup_catalog = catalog   할당 
<img width="781" height="464" alt="image" src="https://github.com/user-attachments/assets/1c86c970-373f-43fe-9b1b-51cb4c879a18" />

그냥 원래 list를 그대로 가져옴 (복사가 아님)



backup_catalog = catalog.copy()   얕은 복사
<img width="778" height="546" alt="image" src="https://github.com/user-attachments/assets/0c7be1bd-38c5-43b8-b439-2d4cd187a46a" />

겉의 리스트 껍질만 새로 만들고 내부의 객체 리스트는 기존의 것과 같은 것을 참조함.

즉, 바깥쪽 리스트만 복사되고, 내부 리스트는 원본과 공유함. 

**>> 내부 객체를 변경하면 복사본과 원본 모두에 영향을 미친다.**

backup_catalog = deepcopy(catalog)   깊은 복사
<img width="773" height="742" alt="image" src="https://github.com/user-attachments/assets/ada8ec57-dde2-444f-a7fc-8c406b0a5eab" />

**겉의 리스트뿐만 아니라 내부에 포함된 모든 객체까지 새로 복사**

**원본과 복사본이 완전히 독립적이고, 내부 객체를 변경해도 서로 영향을 주지 않음.**

</details>


<details><summary>List</summary>

```python

list = [1] * 5
print(list)   # [1, 1, 1, 1, 1]







```



</details>


</details>







<details><summary>2025/07/23</summary>

**함수 개념과 여러가지 함수, scope, packing 그리고 람다**

웹 사이트 여러 곳 동일한 신년 인사가 뜬다. 수정하고 싶다. 하나하나 다 들어가서 수정해??

노노 처음에 인사함수를 만들고 그 함수를 필요한 곳마다 사용. 하나만 수정하면 모든 곳에 적용

함수를 쓰면 여러 곳에 `재사용`할 수 있고 `관리`하기 쉽다. 

# 함수


함수란! : 특정 작업을 수행하기 위한 `재사용` 가능한 코드 묶음. 

- 되는 코드를 하나로 묶어 재사용하기에 코드가 깔끔해짐.
- 복잡한 문제를 작은 단위로 나누어 해결하는 프로그래밍 사고력 기를 수 있음.

  함수 왜 씀? >> 재사용성 높아지고, 코드의 가독성과 유지보수성 향상.

예를 들어 두 수의 합. 매번 변수를 더하는 코드를 입력하기보다 sum이라는 함수를 만들어서 이용하는 게 편리

```python

# 함수 정의
def get_sum(num, num2):
   return num1 + num2

# 이후부터는 함수를 호출하여 결과 출력

result = get_sum(1, 2) 

```


함수 호출: 함수 실행 위해 함수의 이름을 사용해 함수의 코드블록을 실행하는 것

# 함수 구조

```python   
def make_sum(pram1, prma2):   # parameter 1, 2가 INPUT값
   """이것은 두 수를 받아      # """ 속이 Docstirng
   두 수의 합을 반환하는 함수입니다.   # 들여쓰기 된 부분 모두 function body
   >>> make_sum(1, 2)
   3
   """
   returm pram1 + pram2      # return value OUTPUT
```

def 함수명(매개변수:함수에 전달되는 값):
   docstring: 설명서
   함수바디: 함수 실행시 수행되는 코드
   return 반환값 

함수 사용 시 호출이 필요! 함수명() 이렇게!

필요한 경우, 인자 argument 전달해야 하고 그 인자는 매개변수에 대입됨.


- parameter INPUT
- doctring: 함수에 대한 설명 """ """ 선택적으로 작성 가능. 협업을 위한. 
- function body: 함수 아래에 들여쓰기 되어있는 코드 블록, 함수가 실행될 때 수행되는 코드를 정의.
- return value OUTPUT: return 이후에 반환값 명시. return문은 함수의 실행을 종료, 결과를 호출 부분으로 반환함.
- 함수에 return 문이 없다면 None이 반환됨

print() 함수는 반환 값이 없음. return이 없음.

파이썬에서 반환 값이 없는 함수는 기본적으로 None을 반환한다고 간주.

<img width="314" height="251" alt="image" src="https://github.com/user-attachments/assets/fb1be9d4-795e-497b-874f-39ce82ebf6a5" />

함수를 호출했기 때문에 안녕이 출력됨. 함수 자체에서 return이 없기때문에 None이 됨

<img width="358" height="425" alt="image" src="https://github.com/user-attachments/assets/67628285-665d-4cd5-8890-32bacb6b6cfc" />


**반환과 출력을 구분해야 함**

print() 함수는 화면에 값을 출력하기만 할 뿐, 반환(return)값이 없음.

```python

return_value = print()
print(return_value)
>>>None

```

return 이 없는 함수를 print(함수)해보면 None이 나옴.

반환이란 어떤 값이 있어야 함. 

합성함수 느낌?


- 매개변수parameter과 인자argument
- 매개변수: 함수를 정의할 때, 함수가 받을 값을 나타내는 변수
- 인자: 함수를 호출할 때 실제로 전달되는 값

```python
def add(x, y):   # x, y는 매개변수
~~

a = 2
b = 3

sum = add(a, b)   # a, b는 인자

```

# 여러 가지 인자

- 인자의 종류 5가지
  위치 인자, 기본 인자 값, 키워드 인자, 임의의 인자 목록, 임의의 키워드 인자 목록

1. 위치 인자
 - 함수 호출 시 인자의 `위치`에 따라 전달되는 인자.
 - 위치인자는 함수 호출 시 반드시 값을 전달 해야 함.
 - 매개 변수는 2갠데 인자는 한 개, 세 개 넣는 경우 에러 뜸(개수 맞추기)

   
2. 기본 인자 값
  - `함수 정의`에서 매개변수에 기본 값을 할당. 위치인자의 연장선?

    def greet(name, age = 30): 
   
  - 함수 호출 시 인자를 전달하지 않으면, 기본값이 매개변수에 할당됨.
  - 인자 전달하면 위치인자 처럼 그냥 할당됨
  - 이 때는 인자를 덜 넣어도 실행되는 것. 하지만 더 넣으면 에러
   
  
3. 키워드 인자
  - `함수 호출 시` 인자의 이름과 함께 값을 전달하는 인자.
  - 특정 매개변수에 값 할당 가능.
  - 위치인자와 달리 인자 순서 중요X 인자 이름 명시
    
    중요: 키워드 인자는 위치 인자보다 뒤에 위치해야 함. 아니면 error 뜸.

   greet(키워드 인자 = 값, 위치인자) 에러
   
   greet(위치인자, 키워드 인자 = 값) 가 맞음

   greet(1,2, defaultl = 3, 4,5) 이런 거 안됨.

    
4. 임의의 인자 목록 AAL
  - 정해지지 않은 개수의 인자를 처리하는 인자. 위치인자?
  - `함수 정의` 시 매개변수 앞에 *를 붙여 사용
  - 여러 개의 인자를 tuple로 처리

    ```python
       def cal_sum(*args):
       print(args)   #(1,100,5000,30) 이것이 튜플!
       print(type(args))   # class tuple
       cal_sum(1,100,5000,30)
   ```

5.  임의의 키워드 인자 목록
  - 정해지지 않은 개수의 `키워드 인자`를 처리하는 인자.
  - `함수 정의` 시 매개변수 앞에 **를 붙여 사용
   여러 개의 인자를 dictionary로 묶어 처리함. (딕셔너리가 생성!)

      def print_info(**kargs):
         print(kargs)

      print_info(name = 'Eve', age =30)

      >>> {'name':'Eve', 'age':30}

   - 함수 정의 시 인자 권장 작성 순서
   위치 기본값 가변 가변키워드 순서로 하여 혼란 줄임.
   절대적인 규칙 아니고 상황에 따라 유연하게

def func(pos1, pos2, default_arg = 'default', *args, **args):


<img width="578" height="416" alt="image" src="https://github.com/user-attachments/assets/adc66a48-ea3e-4970-a751-e5fea7d2d86d" />

<img width="735" height="380" alt="image" src="https://github.com/user-attachments/assets/38768267-2a35-43d5-84b1-7c0107f6f009" />



# 재귀함수

함수 내부에서 자기 자신을 호출하는 함수.

끝없이 호출하지 않도록 종료 시점 base case 을 명시해줘야 함.

재귀함수의 예시 - factorial
- 자기 자신을 재귀적으로 호출하여 n!을 계산
- 재귀 호출은 n이 0이 될 때까지 , 종료 조건 설정하여 재귀 호출 멈추게 함.
- 재귀 호출 결과 이용하여 문제를 작은 단위의 문제로 분할하고, 분할된 문제들의 결과를 조합하여 최종결과를 도출

  ```python
  def factorial(n):
     if n == 0:
        return 1   # 종료 조건을 먼저 명시
     else:
        return n * factorial(n - 1)   # 재귀 호출: n과 n-1의 팩토리얼을 곱한 결과를 반환

  ```

  - 5!의 경우 1부터 5까지의 곱인데, 5 * 4! 으로 분할하고, 또 5 * 4 * 3! 으로 분할하고 ... 언제까지? base case에 수렴할 때까지. 팩토리얼은 * 1 까지.
 
재귀함수 특징
- 특정 알고리즘 식을 표현할 때 변수의 사용이 줄어들며, 코드의 가독성이 높아짐.
- 한 개 이상의 base case(종료되는 상황) 존재하고, 수렴하도록 작성.
- 꼭꼭! 종료 조건 명확히 하고, 되는 호출이 종료 조건을 향해야 함.(수렴)
- 단점은 메모리 사용량 많고 느릴 수 있다. 종료 조건 잘못되면 스택 오버플로우 에러 발생 가능. 복잡하면 코드 가독성 저하

왜 써? 문제를 간결하고 직관적으로 표현 가능, 코드 간결하고 수학적 문제 직접적 구현 가능하다.


# 내장 함수 built-in function
---
파이썬이 기본적으로 제공하는 함수. 별도의 import 필요 없이 바로 사용 가능

[파이썬 공식 문서](https://docs.python.org/ko/3/)

자습서랑 라이브러리 레퍼런스 언어 레퍼런스 참고하면 좋다

print len max min sum sorted

<img width="477" height="234" alt="image" src="https://github.com/user-attachments/assets/03fb0472-7197-4ec8-b78d-5373410cfd6c" />


# 함수와 scope

python의 범위scope

scope란?

변수나 함수가 유효한 범위. 어디에서 이것을 쓸 수 있는가! (Local Enclosing Global Built-in)

함수는 코드 내부에 local scope를 생성함. 그 외의 공간을 global scope로 구분함.

global scope(코드 어디에서나 참조가능 공간)와 local scope(함수 내부에서만 참조 가능)

global variable(global scope에 정의된 변수)과 local variable(local scope에 정의된 변수)


정의하지 않고 어디에서나 쓸 수 있는 함수 >> built-in scope  예를 들어 print()

정의하고 어디에서나 쓸 수 있는 함수 >> global scope


- 변수 수명주기
글로벌은 코드 실행시부터 프로그램 종료까지.
로컬은 함수 호출 시부터 함수실행 끝날때까지.


함수 내부 전역 변수 사용

x = 5

def test(): 
   global x 
   x = 20

test()
print(x)  #20


global x 으로 x를 글로벌로! 위치가 x=20 보다 아래면 안됨.


이름 검색 규칙

LEGB 룰

로컬 인클로즈 글로벌 빌트인 순으로 이름을 찾아나감.

함수 내에서는 바깥 scope 변수에 접근 가능하지만 수정은 불가능

<img width="667" height="276" alt="image" src="https://github.com/user-attachments/assets/b156efef-e9b2-4ab6-ac7d-63485c763098" />


enclosed는 f함수 내에 g함수가 있는 경우 f와 g 사이의 영역 

안에서 바깥 scope 쪽으로 접근 가능, 반대로는 불가능

<img width="228" height="228" alt="image" src="https://github.com/user-attachments/assets/210edc49-0e84-4d1c-bd55-f6c0a7e65e73" />

<img width="441" height="298" alt="image" src="https://github.com/user-attachments/assets/b410a85b-a6f6-4d63-aca5-0de6297f9ea9" />

<img width="344" height="278" alt="image" src="https://github.com/user-attachments/assets/08222bfb-09bf-4c1c-b3ba-86a1aab00d9c" />
<img width="377" height="305" alt="image" src="https://github.com/user-attachments/assets/20e8af71-f930-499c-811d-d0a9585211c1" />


LEGB 룰 예시

sum은 원래 Builtin 인데 sum = 5 라고 코드를 넣어버리면 sum이 Global 에 오게 됨.

이후 sum을 참조 시 global에서 먼저 찾고 built-in 으로 가기 때문에 sum이라는 내장함수를 이용할 수 없게 됨.

그럴 땐 del sum 으로 삭제 하고 다시 이용


```python


x = 'G'
y = 'G'

def outer_func():
   x = 'E'
   y = 'E'

   def inner_func(y):
      z = 'L'
      print(x,y,z)      # (E, P, L) 

   innter_func('P')
   print(x, y)          # (E, E)  

outer_func()
print(x, y)              #(G, G)

```
<img width="842" height="454" alt="image" src="https://github.com/user-attachments/assets/ede001ae-db63-4676-b9e5-ae680918296a" />

** 함수의 정의와 호출 시점을 잘 봐야 함. **

나의 착각: print(x, y, z) 이후에 inner_func('P')가 왔으니까 y에 P가 들어가는 건 출력된 이후 시점 아닌가?

실제로는 print(x, y, z)는 inner_func(y)의 정의에 속해있을 뿐, 실행된 것이 아님.

실행은 그 아래에 inner_func('P') 라는 호출문이 오면서 실행된 것!

따라서 E P L


# global 키워드

변수의 스코프를 전역 범위 global 로 지정하기 위해 사용

일반적으로 함수 내에서 전역 변수를 수정하려는 경우에 사용함.

num = 0   # 전역 변수
def increment():
   global num   # num을 전역 변수로 선언
   
매개변수에는 global 사용 불가능.

# 함수 이름 작성 기본 규칙

- 소문자와 언더스코어_ 사용
- 동사로 시작. 함수의 동작 설명
- 약어 사용 지양. 길게, 기능 분명하게 쓰기
- 동사 + 명사 / 동사 + 형용사 + 명사 / get set _ 접두사
- calc_price가 아니라 calculate_total_price
- true False 반환시 이름 시작을 is_ 또는 has_ 


단일 책임 원칙. 

모든 객체는 하나의 명확한 목적과 책임만을 가져야 함.

함수 설계 원칙
- 명확한 목적 (한 가지 작업만 수행)
- 책임 분리 (데이터 검증 처리, 저장 등을 별도 함수로 분리, 독립적으로 동작하게 설계)
- 유지보수성 (작은 단위 함수로 나누어 관리. 코드 수정 시 영향 범위 최소화)


# 패킹과 언패킹

여러 개의 데이터를 하나의 컬렉션으로 모아 담는 과정. 

여러 개의 값을 하나의 튜플로 묶는 파이썬의 기본 동작.

한 변수에 콤마, 로 구분된 값을 넣으면 자동으로 튜플로 처리


- *를 활용한 패킹 (함수 매개변수 작성 시)
  남는 위치 인자들을 튜플로 묶기. *를 붙인 매개 변수가 남는 위치 인자들을 모두 모아 하나의 튜플로 만듦.

   args 말고 다른 매개변수 사용해도 되는데 *args 는 암묵적 합의

- **를 활용한 패킹 (함수 매개변수 작성 시)
  남는 키워드 인자들을 딕셔너리로 묶기

  **를 붙인 매개변수가 남는 키워드 인자들을 모두 모아 하나의 딕셔너리로 만듦.

<img width="546" height="210" alt="image" src="https://github.com/user-attachments/assets/e632cc43-6f58-43da-bc80-0d0c6c6e6c75" />


<img width="841" height="38" alt="image" src="https://github.com/user-attachments/assets/757e9538-3f22-4a75-8254-6a0f577ef7ef" />

위치 인자와 end = ' ' 순서 바꿔보고 이것 저것


언패킹: 컬렉션에 담겨 있는 데이터들을 개별 요소로 펼쳐놓는 과정

튜플이라 리스트 등 객체의 요소들을 개별 변수에 할당!

시퀀스 언패킹 또는 다중 할당 이라 부름

packed_values = 1, 2, 3, 4, 5      튜플

a,b,c,d,e = packed_values     다중 할당

print(a,b,c,d,e) 하면 1 2 3 4 5 


*활용

def my_func(x,y,z):
   print(x,y,z)

names = ['a','b','c']

my_func(*names)       a b c

*을 붙여야지만 함수의 개별 위치인자로 할당됨



**활용 (딕셔너리 넣으면 value만 나옴)

def my_func(x,y,z):
   print(x,y,z)

dict = {'a':1, 'b':2, 'c':3}
my_func(**dict) 하면 1 2 3 


패킹: 함수 정의 시 def func(*args): 사용. 여러 위치/키워드 인자를 하나의 튜플/딕셔너리 로 받음

호출해서 받은 인자를 튜플이나 딕셔너리로 묶어주는 거

언패킹: 함수 호출 시 func(*리스트,튜플) 사용.  개별 위치 인자 키워드 인자로 전달

호출해서 받은 튜플이나 딕셔너리를 개별로 풀어쓰는 것


# 참고

- 함수와 반환

파이썬 함수는 언제나! 단 하나의 값(객체)만 반환할 수 있음.

여러 값을 반환하는 경우에도 하나의 튜플로 패킹하여 반환하는 것임.
<img width="388" height="251" alt="image" src="https://github.com/user-attachments/assets/8334c49d-fb43-4772-98cd-4fe501008241" />

name과 age 두 값을 반환하는 거 같지만 실제로는 하나의 튜플을 반환함.



- 람다 표현식

익명 함수를 만드는 데 사용되는 표현식. 한 줄로 간단한 함수를 정의 (def같은 거 없이)

구조: lambda 키워드 , 매개변수(표현식임), 표현식(결과값 반환)

<img width="416" height="225" alt="image" src="https://github.com/user-attachments/assets/c0fc5168-1905-4953-b389-1a2c014b6641" />
<img width="675" height="326" alt="image" src="https://github.com/user-attachments/assets/92567e4b-26f5-49b7-9da1-5203b78ce46b" />

lambda 매개변수 : 표현식

map(함수, 객체)

  
</details>


<details><summary>2025/07/24</summary>

** 모듈과 제어문 조건문 문 **


모듈을 활용해 필요한 기능을 가져와 효율적 코드 작성!

제어문을 통해 특정 조건에 따라 코드를 실행할 수 있음.

특정 작업 여러 번 하도록 지시하여 복잡 문제 쉽게 해결!


# 모듈

한 파일로 묶인 변수와 함수의 모음! 특정 기능 하는 코드가 작성된 파이썬 파일.py

우리는 검증된 코드를 이용함. 다른 프로그래머가 작성한 변수나 함수들의 모음을 모듈이라고 함!

예시) math 내장 모듈 
import math 하고 print(math.pi) print(math.sqrt(4)) 

1. 모듈 활용
- import 문 활용
  동일 이름 함수가 여러 모듈에 존재할 때 충돌 방지 . 연산자 >> math.pi math.sqrt()
- from 문 활용
  from math import pi, sqrt 하고 print(pi), print(sqrt(4))
  코드 짧아지지만 비명시적 타 변수나 함수와 겹쳐져서 동작 안될 수 있음.

  마지막에 import 된 것이 유효. from math import * 는 비추

  - as 키워드
    이름 충돌 해결 from math import sqrt
    from my_math import sqrt as my_sqrt

    함수 변수명 짧게 import pandas as pd
    


2. 사용자 정의 모듈
   직접 정의한 모듈 사용 가능

   먼저 my_math.py 라는 모듈을 생성 def add(x,y): return x+y

   같은 위치(동일 폴더 내)에 sample.py 파일 생성하고 my_math 모듈의 add 함수 import 하고 add 함수 호출

   import my_math

   print(my_math.add(1,2))
   

# 패키지

연관된 모듈들을 하나의 디렉토리에 모아 놓은 것 (코드 꾸러미)

마이패키지 폴더 생성 >> 그 안에 math 폴더와 statistixs 폴더 생성 >> 각 폴더 내부에 my_math.py 와 tool.py 파이썬 파일 생성 후 코드 작성(모듈)

마이패키지 폴더에 sample.py 생성하고 >> from my_package.math import my_math  마이패키지 폴더 안의 math 폴더에서 my_math라는 모듈을 import 한다! from 폴더명 import 파이썬파일 >> print(my_math.add(2,3)) : my_math 파이썬 파일 내에 정의된 함수 add 를 사용


패키지 종류는 1. PSL 내부 패키지 파이썬 설치시 자동 설치. 설치없이 import 해서 사용 2.파이썬 외부 패키지 pip로 직접 설치 

라이브러리: 여러 패키지를 포함 
라이브러리>패키지>모듈


<img width="1165" height="528" alt="image" src="https://github.com/user-attachments/assets/144a5a11-bca7-411e-ac1b-3710458e169a" />



</details>


<details><summary>2025/07/25 관통프로젝트</summary>

총 10회의 프로젝트 과정 

10 번째는 최종 프로젝트 (총 합친 느낌?)

금융 상품 비교 앱 / 영화 추천 서비스 / 도서 정보 검색 서비스 택 1 또는 자유 주제(필수 기능은 포함되어야 함)도 가능

기술은 django와 vue로 고정. react나 다른 거 못씀

**API 이해하기**

오늘은~ 날씨 정보 가져와서 내가 원하는 정보만 출력!

날씨 데이터가 필요! but 직접 모아?! 노노 >> 인터넷에 있는 데이터를 가져오자

어떻게?

서버와 클라이언트 : 클라이언트가 서버에게 정보 요청하면 서버가 클라이언트한테 줌 


날씨 정보 가진 서버한테 정보 줘! 해서 받기 

1. 먼저 서버에 요청을 해보자
   - 웹 브라우저(크롬) 주소창에 주소 URL을 입력한다.
     ex) https://fakestoreapi.com/carts
     but chrome 상의 정보는 활용이 불가능
   - 서버에 정보를 요청하는 파이썬 코드를 작성한다.
     vsxode terminal 열어서 서버에 요청 보내는 도구 pip install requests 설치 후 이용

     (pip: 다른 사람이 만든 파이썬 코드 설치 도구)

     (requests: 파이썬에서 서버에 요청을 보낼 수 있는 도구)

     requests.get(url) : 해당 서버(url)에 데이터 달라고 요청하는 함수

     .json() : 내부 데이터를 json(파이썬 딕셔너리와 유사) 형태로 변환해주는 함수

     **json**
      
     api가 사용하는 데이터 형식: json java script object notation

     데이터 저장 또는 전송 시 많이 사용되는 경량의 텍스트 기반 데이터 형식! (물론 파이썬 패키지 json 도 있음. 동명이인 느낌)

     데이터는 중괄호 키 값 형태로 표현됨.

     json 형식은 문자열임. 엄연히 딕셔너리랑은 다름. json.loads()로 파이썬 딕셔너리로 변환 가능   

     
2. 서버는 어떻게 요청을 해석할까?
   - 여러 방식으로 요청을 받은 서버. 각각 어떻게 해석하지?
   - **API**
     클라이언트가 원하는 기능을 수행하기 위해 서버 측에서 만들어 놓은 프로그램. 기능: 데이터 저장, 조회, 수정, 삭제 등

     서버 측에 특정 주소로 요청이 들어오면 정해진 기능을 수행하는 API를 미리 만들어 둠. (클라이언트는 서버가 미리 만들어 놓은 주소로 요청을 보냄)

     오픈 API: 무료 개방. openweathermap api / 금융상품통합비교공시 api / 알라딘 ~~

        -주의: API KEY 발급 받아서 데이터 요청 시 함께 보냄(정상 사용자 인증), 오픈 API 사용량 제한되어 있음(공식 문서 사용량 제한 확인 필요. 요금 청구됨)


     
     
날씨 정보 제공해주는 API

OpenWeatherMapAPI


</details>


<details><summary>2025/07/28</summary>


** 데이터 구조와 시퀀스에서의 메서드(문자열, 리스트) 그리 복사 **


# 데이터 구조

: 각 데이터의 효율적인 저장과 관리를 위한 구조를 나눠 놓은 것. 프로그램의 성능과 효율성 유지보수성에 큰 영향 미치는 개념

객체란? 메모리 주소 + 타입 + 값 (메모리와 구조 측면에서 설명)
데이터 + 메서드 ( 객체지향 프로그래밍 관점) 

즉 객체는 상태와 행동을 함께 가진 단위!!!!!!

# 메서드
:클래스 내부에 정의되는 함수 (클래스는 객체를 만들기 위한 설계도)

객체: `데이터`와 데이터 처리하는 `기능`(메서드)를 묶은 것

메서드: 객체가 가진 함수(행동) 

데이터 구조마다 고유한 메서드를 가짐. 메서드를 호출하여 다양한 기능 활용하기



메서드는 객체에 종속된 개념이기 때문에 호출 방법은 : 데이터 타입 객체.메서드() 

ex) 'hello'.capitalize()    numbers.append(4)   리스트 추가

위와 같이 객체(데이터)에게 명령(메서드)를 내림


# 시퀀스 데이터 구조 (문자열과 리스트) 에서의 메서드

1. 문자열

(1) 문자열 조회/탐색 및 검증 메서드

주의: 문자열이므로 항상 따옴표를 써야 함. 이걸로 실수하지 말자......

문자열은 불변 객체이므로 항상 메서드가 값을 반환함. 

s.find('s') : s의 첫 번째 `위치인덱스`를 `반환`. 없으면 -1 반환 / s.index('s') find와 유사하나 없을 때 오류

찾아! find하면 있군 ! 인덱스, 없군! -1 // .index() 뭐야! 여기있군 ! 인덱스 반환 뭐야 어딨어! 오류

s.isupper() s.islower() s.isalpha(): 문자열 내 모든 문자 대문자인가?소문자인가? 알파벳인가? (한글도 알파벳) True 숫자 들어가면 False


(2) 문자열 조작 메서드(새로운 문자열 반환)

문자열.replace(old, new[,count]) 앞에서부터 count만큼 바꿈. 안 쓰거나 0이하면 싹 다 바꿈 

(old new 들어가는 건 문자열이므로 항상 따옴표 필요 "")

문자열.strip([chars]): 문자열의 시작과 끝에 있는 공백 혹은 지정한 문자를 제거
<img width="281" height="246" alt="image" src="https://github.com/user-attachments/assets/35e54cd4-1ee2-4120-add9-3fb67bad3b17" />
<img width="311" height="257" alt="image" src="https://github.com/user-attachments/assets/d75ec9b2-4f82-4e2b-81e6-00fe1d1f8acd" />


문자열.split(sep = None, maxsplit = -1) : sep를 구분자 문자열로 사용하여 문자열에 있는 단어들의 `리스트`를 반환함
<img width="295" height="249" alt="image" src="https://github.com/user-attachments/assets/f86e5910-40f6-4c5e-9f9c-8da3b49d7119" />


'separator'.join(iterable) : 구분자(separator)로 iterable( 가능) 의 문자열을 연결한 문자열을 반환!

리스트의 각 값 사이사이에 separator 가 들어감. 리스트 값들 사이사이에 뭔가를 넣은 문자열을 만들고 싶을 때 사용 가능


'-'.join(words) 는 이터러블한 words라는 리스트 속 값들을 -로 연결하여 문자열로 반환 

그 외 : .capitalize() 가장 첫 대문자로 / .title() 띄어쓰기 기준 각 첫 글자 대문자로, 나머지 소문자로 / .upper() 모두 대문자 .lower 모두 소문자 / .swapcase() 대소문자 서로 변경



# 리스트 

가변 객체: 리스트, 딕셔너리, 집합과 같이 원본 데이터를 직접 수정 가능

원본을 바꾸는 메서드 반환값이 없다. (새로운 객체를 만들지 않고 자기 자신을 수정하기 때문에)

(함수에서 반환값이 없으면 None을 반환했다. print(print('x')) 처럼. 메서드는 함수의 일종이라 생각)

<img width="342" height="155" alt="image" src="https://github.com/user-attachments/assets/c1af3e7e-401e-429f-8ab3-44f39a36833c" />

my_list는 append()가 호출되어 4를 추가하는 직접 변경! 직접 변경했기 때문에 새로운 리스트를 만들어서 반환하는 것이 아님. >> None을 반환 

하지만 불변 객체에서는 문자열.upper() 같은 건 변경이 불가능하기 때문에 새로운 객체를 만들어서 반환
<img width="346" height="151" alt="image" src="https://github.com/user-attachments/assets/54ced545-27c2-4ed6-bde4-08fb069153ac" />


(1) 리스트 값 추가 및 삭제 메서드

L.append(x): 리스트 마지막에 x 추가 (하나만)
<img width="271" height="188" alt="image" src="https://github.com/user-attachments/assets/37a7593e-76d6-42e3-ae9a-b27f79983f23" />

L.extend(iterable) : 리스트에 다른  가능한 객체의 모든 항목을 추가! 여러 개 추가 가능

가능객체(iterable): 문자열, 리스트 튜플 딕셔너리 집합 range

구분: for i in 객체 가능 여

사용예시: for i in 'strange': ~~

for i in 10: 정수 10 안에 포함된 i 같은 건 없음


 불가능 객체: 정수, 실수, 불리언, Nonetype 


L.insert(i,x): 리스트의 지정한 인덱스 i 에 항목 x를 삽입 ! (다른 값 그대로 두고 원하는 것만 삽입)

L.remove(x) 리스트에서 첫 번째 x를 제거. 항목 없으면 value error

L.pop() 리스트 가장 오른쪽(마지막) 항목을 `반환` 후 제거

L.pop(i) 리스트 중 인덱스가 i인 항목을 반환 후 제거

L.clear() 리스트 모든 항목 삭제


.reverse() : 리스트 순서를 역순으로 변경. 정렬은 아님. (정렬은 오름,내림차순같은 것)
<img width="412" height="218" alt="image" src="https://github.com/user-attachments/assets/3a11f2e8-6055-4b6b-8ae7-a173658da87a" />


.sort() 원본리스트 오름차순으로 정렬
my_list.sort() 
내림차순은 my_list.sort(reverse=True)   reverse 가 내림차순이라 생각하면 될 (할 때마다 반대 정렬이 아니고 그냥 고정)


반환값 유무
<img width="339" height="158" alt="image" src="https://github.com/user-attachments/assets/2fe9251c-d60b-4234-babe-dbc347fddbc0" />

<img width="262" height="179" alt="image" src="https://github.com/user-attachments/assets/8484a2c7-d98a-4a2f-a757-4d8ecefec26f" />











# 복사

1. 객체와 참조

** 가변과 불변 구분 ** 


- 가변 객체
  <img width="233" height="342" alt="image" src="https://github.com/user-attachments/assets/ffccd75b-ef6d-4626-98b5-a4a322a380c8" />

리스트에서 b = a는 할당한 것. 복사된 것이 아님. 아예 동일함
생성 후 내용 변경 가능. 객체 내용 변경 되어도 같은 메모리 주소 유지(새로운 생성이 일어나지 않음)
<img width="749" height="180" alt="image" src="https://github.com/user-attachments/assets/ff022ac8-16ed-4e7a-9215-98f1561f6614" />


- 불변 객체
<img width="227" height="195" alt="image" src="https://github.com/user-attachments/assets/dca64641-075f-42ca-9108-8922c27dde32" />
정수는 불변 객체. a가 바뀐다고 b가 바뀌지 않음. 
생성후 변경 불가. 새로운 값 할당 시 새로운 객체 생성되고 변수는 새 객체를 참조하게 됨.
<img width="412" height="120" alt="image" src="https://github.com/user-attachments/assets/6675705c-7813-4f5a-aeaf-ee160d1e0c0f" />
<img width="420" height="138" alt="image" src="https://github.com/user-attachments/assets/ce63ab3c-4c9a-47ff-a383-3e150d5c4f99" />

  
2. 얕은 복사

객체의 `최상위 요소`만 새로운 메모리에 복사하는 방법. 

내부에 중첩된 객체 있다면 그 객체의 참조만 복사됨. 

얕은 복사의 함정 '가변 객체' 


- 얕은 복사 방법



- 얕은 복사의 한계
객체의 최상위 요소까지만 복사된다는 말.

리스트 내에 리스트가 있는 경우 그 리스트는 복사된 것이 아니라 동일한 객체를 참조.
>> 2차원 리스트와 같이 변경 가능 객체 내에 변경 가능 객체가 있는 경우.

따라서 얕은 복사는 1차원 리스트에서만 복사본 생성 가능. 다차원 리스트에선 최상위 리스트만 복사되고 내부는 여전히 원본과 같은 객체를 참조





# 깊은 복사

객체의 모든 수준의 요소를 새로운 메모리에 복사하는 방법. 중첩된 객체까지 모두 새로운 객체로 생성

원본 객체와 복사본이 완전히 독립. 영향주지 않음.

- 깊은 복사 방법
  copy 모듈 이용. deepcopy() 함수를 사용함.
  import copy 하고 new = copy.deepcopy(original)


# 참고 List Comprehension와 method chaining

간결하고 효율적인 리스트 생성 방법! 파이써닉하다~ 파이썬 답게 코드를 작성하는 방법 중 하나

리스트 생성법 3가지

for loop, list comeprehension, map

성능 비교 : 일반적으로 comprehension map for loop 순서로 빠름 그러나 차이 미미 
  
따라서 코드의 가독성과 유지보수성을 최우선으로 고려하여 선택하기



메서드 체이닝 : 여러 메서드를 연속해서 호출하는 방식

앞 메서드에서 반환 값이 없다 None이라면 문제 발생!!!

예시


앞 메서드의 반환값이 뒤 메서드가 기능 가능한 타입이어야 함

**메서드 별 반환 유무에 대한 파악**

불변 객체라면 항상 새로운 객체를 생성하므로 메서드 체이닝이 편함.


추가 : 문자 유형 판별 메서드



sort와 sorted

numbers.sort(): 정렬. (반환값 없음)
리스트 객체의 메서드. 원본 리스트를 변경하고 반환값은 None 

sorted(numbers)
내장 함수. 원본 그대로 두고 정렬된 새 리스트를 반환함.


</details>


<details><summary>2025/07/29</summary>

**비시퀀스 데이터구조(딕셔너리,세트)의 메서와 해시테이블**

# 딕셔너리

내부적으로 `해시 테이블` 사용하여 키-값 쌍을 관리.

키를 통한 값의 삽입, 삭제, 검색이 데이터의 크기와 관계없이 매우 빠름!

키는 hashable한 고유 값이어야 하지만 값value 는 중복 가능, 어떤 자료형도 저장 가능.


딕셔너리 메서드 11가지
D.get(k) D.get(k,v)   /   D.keys() D.values() D.items()   /   D.pop(k) D.pop(k,v)

D.clear()   D.setdefault(k)   D.setdefault(k,v)   D.update(other)   

D.clear() 과 D.update(other)  이 둘은 딕셔너리 내부를 변경할 뿐 반환이 없음. None


1. Dict.get(key)
   키 값게 연결된 값을 반환. 키 가 없으면 None을 반환함.

   이전에 dict[key] 와 유사. 차이점은 키가 없을 때 얘는 error가 뜸 get은 None을 반환

1-1 Dict.get(key,default) 

default는 선택 가능 ( 키 값이 없을 시 default가 반환됨. default 설정 안하면 None)
<img width="365" height="169" alt="image" src="https://github.com/user-attachments/assets/2f1ec8e5-cb85-43fa-958c-0437844d5475" />

2. Dict.keys()

딕셔너리 키를 모은 객체를 반환. dict_keys라는 객체를 반환하는데 이는 뷰view객체라고 함.


<img width="316" height="263" alt="image" src="https://github.com/user-attachments/assets/e63db909-a496-4838-aefc-d771cbe9e807" />
아래와 같이 dict_keys type으로 키만 반환
<img width="300" height="136" alt="image" src="https://github.com/user-attachments/assets/26b43927-0ad4-42f2-a813-b487189dc80e" />
for 반복문에 이용 가능, set처럼 동작, 실시간 반영 하지만!! 인덱싱은 불가능 
(이터러블하지만 딕셔너리라 인덱싱은 불가하다.)


3. Dict.values()

딕셔너리 값을 모은 객체를 반환
<img width="301" height="106" alt="image" src="https://github.com/user-attachments/assets/347751fe-aef4-479c-a54e-b8d2e0d5af09" />

4. Dict.items()

딕셔너리 키/값 쌍을 모은 객체를 반환

<img width="507" height="218" alt="image" src="https://github.com/user-attachments/assets/170e8466-7b98-4127-b10e-dee6e0b4f0ff" />

for 문에서 임시변수 두 개 선언하여서 각각 출력
<img width="284" height="128" alt="image" src="https://github.com/user-attachments/assets/1d14eb2b-d808-4160-82d0-d27cca25e28a" />

임시 변수 하나만 설정 시
<img width="299" height="156" alt="image" src="https://github.com/user-attachments/assets/0b9efd36-cdb0-4930-a458-1ed3ca3853af" />


5. Dict.pop(key [,default])

키를 제거하고 연결됐던 값을 반환. 없으면 에러 default 있으면 default 를 반환

<img width="354" height="261" alt="image" src="https://github.com/user-attachments/assets/b06ec93d-691b-424d-8968-f1ab1a09b2a4" />

6. Dict.clear()

딕셔너리 모든 키 값 쌍을 제거(반환값은 없음.)

<img width="378" height="217" alt="image" src="https://github.com/user-attachments/assets/bb65ffc0-1cd3-4a8c-b79b-031dc765afc9" />



7. Dict.setdefault(key[,default])

키와 연결된 값을 반환함 .get(key) 와 유사

그런데!! 키가 없는 경우 default와 연결한 키를 딕셔너리에 `추가`하고 default를 반환함.

.get(key) 메서드 + 딕셔너리에 추가
<img width="379" height="277" alt="image" src="https://github.com/user-attachments/assets/7a33a342-4be1-40c4-b17e-3c2d8cf0274c" />

키가 존재 시 값을 반환, 키가 없을 시 default를 반환하는 동시에 딕셔너리에 키 : default 한 쌍을 추가하게 됨


8. Dict.update([other])

other이 제공하는 키/값 쌍으로 딕셔너리를 갱신하고 기존 키는 덮어씀

두 가지 방식

- other 이 딕셔너리인 경우
  <img width="434" height="164" alt="image" src="https://github.com/user-attachments/assets/cd4c5469-1443-4b68-8ce6-275fe73ed43a" />



- other 이 키 = 값 형태로 주어진 경우. (key는 따옴표가 없음)

<img width="401" height="132" alt="image" src="https://github.com/user-attachments/assets/fee297d0-a9ea-4f8e-8349-557b5c53a17f" />



# 세트 Set 
`고유`한 항목들의 `정렬되지 않은` 컬렉션.

Set는 내부적으로 해시 테이블을 사용하여 데이터를 저장함.

항목의 고유성 효율적 보장, 항목의 추가 삭제 존재 여부 확인 (in 연산)이 데이터 크기 관계 없이 매우 빠름

합집합, 교집합, 차집합 등 수학적 집합 연산을 간편하게 수행 가능

리스트의 중복을 제거하고 싶다면 set로 형 변환 하고 다시 리스트로 형변환 but 순서 보장이 안됨(순서 유지해야하면 못 씀)


set의 메서드 6가지

s.add(x) s.update(iterable)   s.clear   s.remove(x)   s.pop()   s.discard(x)

s.pop() 만 반환이 있음.

1. set.add(x)
set에 x 추가. 이미 있다면 변화 X
순서가 없기때문에 print시 매번 무작위로 출력

2. set.update(iterable)

set에 다른 iterable 요소를 추가함

<img width="493" height="179" alt="image" src="https://github.com/user-attachments/assets/0754c6cb-b982-44d7-8226-7d6d868998cf" />
<img width="372" height="158" alt="image" src="https://github.com/user-attachments/assets/79e3e30a-5f26-4f6e-a7b5-501eaafbb904" />

3. set.clear()

모든 항목 제거. print하면 set() 이 출력. {}는 딕셔너리라

4. set.remove(x)

set에서 항목x를 제거. (반환은 없음) x가 없을 경우 keyError 뜸

5. set.pop()

set에서 임의의 요소를 제거하고 반

임의의 != 랜덤(무작위) 

아래 참고에서 더

6. set.discard(x)

세트 s에서 항목 x를 제거. remove와 달리 x가 없어도 에러 없음

상황에 따라 remove와 discard 적절히


그 외 set의 집합 메서드와 그에 대응되는 set 연산자

set1.difference(set2) 

set1.intersection(set2)

set1.issubset(set2)

set1.issuperset(set2)

set1.union(set2)


# 해시 테이블

해시 테이블: 키와 값을 짝지어 저장하는 자료 구조

ex) 책 찾을 때 
리스트라면 모든 요소 순회하여서 찾아내야 하는 사고
딕셔너리로 책 이름(키) 넣으면 위치 알려줌. 그런데,,, 어떻게 키를 한 번에 찾아내지? 

사실 키와 인덱스 사이에는 해시 함수가 있었다!!

키   >    해시함수     >   해시값(위치)

해시함수가 키를 받으면 해시값으로 변환시킴. 

변환된 해시 값을 인덱스로 삼아 데이터를 저장하거나 찾음

이 과정을 통해 검색 삽입 삭제를 매우 빠르게 수행함.


**해시**
해시: 임의의 크기를 가진 데이터를 고정된 크기의 고유한 값으로 변환하는 것 

생성된 해시값(고유한 정수) 는 해당 데이터를 식별하는 지문 역할을 함. 

파이썬은 이 해시값을 이용해 테이블에 데이터를 저장.

이 변환을 수행하는 것이 해시 함수!!

**해시함수**

해시 함수: 임의 길이 데이터를 입력 받아 고정 길이(정수)로 변환해주는 함수. 이 정수가 바로 해시 값

주로 해시 테이블을 구현할 때 매우 빠른 검색 및 데이터 저장 위치 결정을 위해 활용함.

해시 알고리즘이라고도 부름

해시테이블이 매우 빠른이유: 해시 함수는 키를 입력 받아 데이터를 저장하거나 찾을 배열의 '정확한 인덱스'를 계산. 
마치 책의 제목(키)를 알면 색인(해시함수)를 통해 페이지 번호(인덱스)를 바로 알아내고 해당 페이지(배열 위치)로 곧바로 이동하여 내용을 찾는 것과 같음.



set의 요소와 dict의 키와 해시테이블 관계

set의 각 요소를 해시 함수로 변환해 나온 해시 값에 맞춰 해시 테이블 내부 버킷에 위치시킴

순서라기보다는 버킷 위치(인덱스)가 요소의 위치를 결정

매 실행마다 해시 함수 결과 달라지고 set 요소 또한 순서를 보장하지 못하게 됨

dict의 key 가 해시함수를 거쳐 해시 값이 나옴. 이 해시값을 해시 테이블에 저장함. 

set과 달리 dict의 삽입 순서는 유지한다는 것이 언어 사양에 따라 보장됨 
즉 키를 추가한 순서대로 반복문 순회할 때 나오게됨.
사용자에게 보여지는 키 순서는 삽입 순서가 유지되도록 설계된 것.

둘 다 비시퀀스. 인덱스가 있다는 건 아니다.


앞서 set의 pop 메서드 

pop의 순서는 버킷의 순서대로임.

- 숫자로만 이루어진 my_set에서 
print(my_set.pop()) 을 반복하면 모두 다 동일한 순서대로 정수가 출력됨.

오름 내림처럼 특별한 정렬이 있는 건 아니라 `임의의`라고 표현하지만 각 정수의 버킷 순서가 고정적이라  pop 반환 순서 동일

같은 정수는 항상 같은 해시 값을 가짐. (일정)

문자열과 섞이면 정수는 버킷위치 일정하지만 문자열의 버킷위치가 계속 바뀌게 됨



- 문자열로 이루어진 my_set
문자열은 해시 계산 시 파이썬의 해시 난수화가 적용되므로 실행마다 순서가 달라짐.

문자열 해시 시 파이썬 인터프리터 시작 때 설정되는 난수 시드가 달라질 수 있음. 
보안 위해 난수화 도입. 각 실행마다 달라질 수 있어 'a'의 해시 값도 매번 바뀔 수 있음.



가변 객체는 hashable 하지 않다.


# 파이썬 문법 규격

BNF 프로그래밍 언어 문법 표현 위한 표기법

EBNF BNF 확장. 메타 기호 추가하여 더 간결, 표현력 강해진 형태

메타 기호 : [] 선택 요소 {} 0번 이상 반복 () 그룹



</details>

<details><summary>7월 월말 평가</summary>

# 단원 테스트는 출력값 
and와 or 의 활용이 아쉬움
x = '' and 52 or 25
print(x)

x = 5
y = 7
z = 5
print(x=y or y = 1 and not z) 


깊은 복사 서술형에서 조금 더 정확한 용어로 서술할 수 있도록 

.split .seq 헷갈렸음 아직 모르긴 함. 

문제는 심플하게 나옴. 해시같은 딥한 개념은 나오지도 않았음.


# 월말 평가

수업시간에 한 내용 많이 나옴. 수준이 들쭉날쭉

**팁! 구하고자 하는 것을 변수로 만들어 두기!**

내가 지금 구하고 싶은 것을 먼저 파악


아쉬웠던 점: 2번 문제

주어진 문자열의 리스트 중 가장 긴 문자열을 반환하는 함수 

1번 문제는 점수들을 순회하며 최댓값을 반환하는 것이라 각 객체 자체를 비교하면 됐음

2번 문제는 문자열이기 때문에 문자열의 길이를 숫자로 바꾸고, 비교를 해야 함. 하나의 과정이 추가

생각을 모든 문자열의 길이를 각각 구해서 모두 비교하고 가장 큰 애를 인덱스로 가져오려고 했음. 미친 생각 ;; 

그냥 1번의 응용형

1번은 첫째 값을 가장 큰 값으로 잡고, 이후 비교하면서 큰 걸 넣으면 되는데

2번은 문자열이라 문자열의 길이의 최솟값은 0임. 첫 문자의 길이를 굳이 구해서 기본값으로 잡을 필요가 없음
따라서 기본을 0으로 잡고 이보다 큰 것을 넣으면 되는 것 

max_v = list[0]

for num in list:
   if max_v < num:
      max_v = num

longest_str = ''
longest_l = 0

for lst in str_list:
   length = 0:
      for idx in lst:
         












</details>


<details><summary>2025/07/30</summary>

**OOP object oriented programming 객체 지향 프로그래밍과 클래스, 메서드**

OOP의 관점에서 본 클래스와 객체 인스턴스 메서드. 패러다임!

클래스와 인스턴스의 차이를 이해하고 구분하기

클래스 내부에 변수와 메서드를 정의

인스턴스를 생성하고 인스턴스 변수를 활용

인스턴스 메서드, 클래스 메서드, 스태틱 메서드의 차이를 설명   



# 프로그래밍 패러다임

절차 지향과 객체 지향

1. 절차 지향 프로그래밍

함수와 로직 중심 작성. 데이터를 순차적으로 처리.

모든 과정이 위에서 아래로 차례차례 흐름. (입력 받고 처리하고 결과를 내는 과정)

- 변수와 함수를 별개로 다룸. 함수의 호출 흐름이 중요 

마치 레시피

데이터 있고 함수 있고 함수 호출해서 데이터 넣음

한계: 복잡성 증가(규모 커질수록 데이터 함수 관리 어렵) 코드 수정 시 영향 범위 파악 어려움

항상 처음부터 끝까지 코드를 실행하다보니...



2. 객체 지향 프로그래밍

클래스는 설계도, 인스턴스는 실제 물건

자동차를 만들기 위한 설계도 : 클래스 

설계도 바탕으로 조립된 자동차 : 인스턴스

같은 종의 자동차라도 색상이 다를 수 있듯, 인스턴스는 서로 다른 속성 가질 수 있고

파이썬에서도 클래스를 정의한 뒤 클래스를 바탕으로 여러 개의 인스턴스를 만들 수 있다.


객체 지향 프로그래밍의 특징: 프로그램을 데이터(변수)와 그 데이터를 처리하는 함수(메서드)를 하나의 단위(객체)로 묶어서
조직적으로 관리

즉, 데이터와 메서드의 결합

주방 도구(프라이팬), 재료(고기), 행동(볶기) 를 각각 별개로 생각하지 않고
볶음밥 기계! 라는 객체로 만들어 놓고 그 기계가 행동과 재료를 관리한다!!


# 객체와 클래스

객체란 실존하는 사물을 추상화. '속성'과 '동작'을 가짐
ex) 강아지라는 객체는 이름, 종, 나이 라는 특징과 짖기 뛰기 같은 행동 등으로 표현 가능

클래스란 객체를 만들기 위한 설계도


<img width="657" height="589" alt="image" src="https://github.com/user-attachments/assets/d7f1ff5c-8cff-450d-83b7-87fbd8ed6096" />

가수라는 객체는 직업 나이 같은 속성(변수)과 노래 댄스 같은 동작(메서드)

가수라는 클래스에서 아이유 BTS 같은 객체


# 클래스

클래스는 하나의 구조 안에 데이터(변수)와 기능(함수)를 함께 정의하는 도구

서류 양식이 있다 치면 양식이 클래스, 채워진 서류는 인스턴스

클래스는 데이터 (속성) 과 기능(메서드) 함께 정의해 여러 인승턴스를 일관되게 만들어내는 틀 역

속성과 메서드

클래스 보수적이지만 


# 클래스와 인스턴스

클래스로 인해 만들어진 객체를 인스턴스 (인스턴스는 누구의 객체인지가 중요)

가수라는 클래스

아이유는 객체다. O

아이유는 인스턴스다. X 

아이유는 가수의 인스턴스다 O


클래스를 정의한다는 것은 공통된 특성과 기능을 가진 틀을 만드는 것이다.

실제 활동하는 개별 객체들은 이 틀에서 생성된 인스턴스 

공통된 특성과 기능을 가진 틀을 만드는 것은 곧 새로운 타입을 만드는 행위


# 메서드

클래스 내부에 정의된 함수. 해당 객체가 어떻게 동작할지를 정의

메서드의 종류 3가지: 인스턴스 메서드, 클래스 메서드, 스태틱 메서드

1. 인스턴스 메서드

인스턴스의 상태를 조작하거나 동작을 수행함. (지금까지 배운 모든 메서드가 인스턴스 메서드)

계산기라는 객체. 그 속에 더하기 기능. 각 계산기 인스턴스에서 더하기 메서드 호출 가능

인스턴스마다 독립적으로 행동할 수 있게 만드는 것이 인스턴스 메서드.

인스턴스 메서드 구조: 클래스 내부 정의되는 메서드의 기본

반드시 첫 번째 인자로 인스턴스 자신(self)를 받음. 고정적. 무조건!
인스턴스의 속성에 접근하거나 변경 가능



2. 클래스 메서드

클래스 변수를 조작하거나 클래스 레벨의 동작을 수행

@classmethod 데코레이터를 사용하여 정의 >> 인스턴스 메서드와 구별 

```python
class Person:
   population = 0
   def increase_population(cls):
      cls.population += 1

   @classmethod
   def increase_population(cls):
      cls.population += 1
# 인스턴스를 만들 때마다 추가
```


</details>
 


<details><summary>2025/07/31</summary>


**클래스와 상속 에러와 예외 처리**

# 클래스 상속

상속: 부모 클래스의 속성과 메서드를 자식 클래스가 물려받는 것.

두 클래스 간 상하관계 형성됨. 

상속 과정: 속성과 메서드를 넘겨주는 과정

왜 함? 코드 재사용, 계층 구조 형성, 유지 보수 용이성, 


ex) rpg 게임 공통 속성 상위 캐릭터에서 구현, 직업별 특징 따라 추가 속성 구현


왜 상속이 필요할까?

Person 클래스에 학생과 교수 생성하는 경우, Person class 만 쓰면 둘 각각 가지는 고유 속성 표현 어렵다.
그러면 아예 교수 클래스랑 학생 클래스를 만들어? 그러기엔 `중복되는 메서드`가 존재. 
따라서 `중복되는 공통 속성과 메서드`는 부모 클래스에서 한 번만 정의하고, 필요한 클래스들이 이 부모 클래스를 물려받아 사용하기


다중 상속: 둘 이상 상위 클래스로부터 상속

만약 여러 상위 클래스에 중복된 속성이나 메서드가 있다면 어디서 어떻게 상속받을까?

먼저 작성한 순서로 가겠다.

class FirstChild(Dad, Mom) 이면 Dad의 속성을 갖게 됨( 먼저 찾아서 더 안 찾음)


다이아몬드 문제


'''
   A
  / \
B     C
  \ /
   D  

'''
B와 C가 A에서 상속, D는 B, C 모두에서 상속될 때 발생하는 모호함.
B와 C가 재정의한 메서드가 A에 있고 D가 이를 재정의하지 않음. 

D는 누구의 메서드 버전 상속 ?

MRO 알고리즘 사용. 기본적으로 왼쪽에서 오른쪽. 계층 구조에서 중복되는 클래스는 한 번만 확인

그래서 속성이 D에서 발견되지 않으면, B에서 찾고, 거기서도 발견 안되면 C에서 찾고 ... 

MRO: Method Resolution Order 파이썬이 메서드 찾는 순서에 대한 규칙
- 다중 상속에서 어떤 부모 클래스의 메서드를 먼저 사용할지 순서를 정의함.
- 미리 정해진 MRO 통해 다중 상속 환경에서 예측 가능 방식으로 메서드 탐색 이루어지게 함


super()
- MRO 메서드해석순서에 따라 현재 클래스의 부모 클래스의 메서드나 속성에 접근할 수 있게 해주는 내장 함수

시작점이 중요함 시작점을 기준으로 MRO 순서 형성하기 때문에 ! (유연함) 
단순히 부모 순서가 아님



# 에러와 예외

1. 디버깅: 소프트웨어 발생하는 버그 찾아내고 수정하는 과정
- print 함수 활용
- 개발 환경 txt editor IDE 등 제공하는 기능 활용
- python tutor ,  뇌 컴파일 ~ 

버그: 소프트웨어 오류 결함 / 프로그램의 예상된 동작과 실제 동작 사이의 불일

에러: 프로그램 실행 중 발생하는 예외 상황

에러 유형 2가지: 문법에러 syntax error 과 예외 exception


**예외**
프로그램 실행 중 감지되는 에러

프로그램이 잘못된 동작 시도할 때 자동감지. 처리하지 않으면 프로그램 즉시 종료

내장 예외: 예외 상황을 나타내는 예외 클래스들

이미 파이썬에서 정의되어 특정 예외 상황 처리 위해 사용 

예외 처리exception handling: 예외 발생 시 프로그램이 비정상적으로 종료되지 않고, 적절하게 처리할 수 있도록 하는 방법
- 오류 발생해도 프로그램 흐름 안전하게 이어나감
- try except 구문 사용해 특정 예외 잡아내고 원하는 동작 수행하게 함.
- 예외 처리 구현 시 오류 메시지 보여주거나 대체 로직 실

1. 예외 처리
try-except 구조

try 블록에서 오류 발생 시 except 블록이 실행되어 예외를 처리하는 구조

try:
   예외가 발생할 수 있는 코드
except 예외:
   예외 처리 코드

2. 복수 예외 처리

발생 가능 에러가 여러 가지인 경우

num = int(input('100으로 나눌 값 입력: '))

print(100/num)

먼저 발생 가능한 에러 예상해보기 : 문자 입력 >> ValueError  / 0 입력 >> ZeroDivisionError


else & finally 

else: 예외 발생 않았을 떄 추가 작업. (except 구문 실행 안된 경우)

finally 블록은 예외 발생 여부 상관없이 항상 실행할 코드 작성


주의 사항

Exception 클래스: 모든 error 들의 부모 클래스

try: 
   num 어쩌구
except Exception:
   print()
except ZeroDivisionError:
   print()

이렇게 하면 Exception에서 모든 에러를 가로채버림. 그래서 이보다 아래에 있는 코드는 작동 X

따라서 except Exception: 는 항상 가장 마지막 줄에 넣어야 함.

내장 예외 클래스는 상속 계층구조를 가지기 때문에 except 절로 분기 시 하위 클래스를 먼저 확인 할 수 있게 (위에) 작성



</details>


<details><summary>2025/08/01 PJT2</summary>


# 데이터 사이언스 

데이터 사이언스 기초 이론, kaggle에서 데이터 다운, 데이터 사이언스 자주 사용되는 패키지 학습 

개발도구: python 3.11, Jupyter notebook

Jupyther notebook 브라우저에서 실행 / 코드 실행 / 텍스트 문석 작성, 시각화 등 하나의 문서에 통합 작업 가능

데이터 사이언스에 주피터 노트북 많이 쓰임 왜? 셀 단위 코드 실행으로 블록마다 결과 바로 알 수 있음.

윈도우 cmd 명령 프롬프트 > pip install notebook 주피터 다운로드 >

필요 정보 추출 5단계
1. 문제 정의
2. 데이터 수집
3. 데이터 전처리 (가공. 오류 제거 및 데이터 형식 변환)
4. 데이터 분석 (필요 정보 추출)
5. 결과 해석 및 공유

ex
1. 문제 정의
- 구글의 주식 가격은 앞으로 어떻게 될까?

2. 데이터 수집
- 주식 분석 위해 기간 별 주식 가격에 대한 데이터가 필요
- 데이터 수집 기술, 방법: 웹 스크래핑, 웹 크롤링, Open API 활용, 데이터 공유 플랫폼 활용(kaggle, data world, dacon,공공데이터포털)
kaggle dataset

csv? 몇 가지 필드를 쉼표로 구분한 텍스트 데이터 및 텍스트 파일

표 형식 데이터 csv 형태로 많이 사용. 저장 전송 처리 빠르고 다양 프로그램 처리 가능

3. 데이터 전처리
- 오류 데이터 제거, 중복 데이터 제거, 적절한 형식으로 데이터 변환  
- 데이터 전처리 및 분석에 사용되는 파이썬 패키지: Numpy, Pandas, Matplotlib

- Numpy: 수학 계산용 pandas와 matplotlib 사용위해 활용 (데이터 처리 및 분석)
다차원 배열 쉽게 처리. 효율적 사용. 행렬 연산 빠름

- Pandas: 원하는 데이터만 추추르 데이터 분석 (데이터 처리 및 분석)
numpy의 한계: 유연성 부족, 구조화 부족. pandas가 엑셀 다루듯 고성능 데이터 구조 만들 수 있음.

- Matplotlib: 그래프 그림(데이터 시각화)

파일 들어가서 빈 공간 우클릭 > 터미널에서 열기 > python -m notebook  하면 웹에 해당 파일 주피터 노트북으로 뜸

python example 주피터 노트북 참고





</details>

<details><summary>알고리즘 1</summary>

**리스트와 정렬**

알고리즘은 문제해결!

(자명한 것에 대한 생략 가능)

슈도 코드

시간복잡도: 알고리즘의 작업량. 실제 걸리는 시간 측정, 실행되는 명령문의 개수를 계산

시간복잡도 쵸시는 주로 빅 O 표기법. 시간 복잡도 함수 중 가장 큰 영향력을 주는 n에 대한 항만을 표시

계수는 생략하여 표시

O(3n+2) = O(3n) = O(n) 

O(2n^2 + 10n + 100) = O(n^2)

O(4) = O(1)

# 배열
array

그림 그리는 습관

# 정렬

2개 이상 자료를 키(특정 기준)에 의해 오름 차순 또는 내림차순으로 재배열하는 알고리즘

1. 버블 정렬
- 인접한 두 개의 원소를 비교하며 자리를 계속 교환하는 방식
- 첫 원소부터 인접한 애들 끝까지 쭉~ >> 1단계에 가장 큰 원소가 가장 마지막 자리로.
- 시간 복잡도 O(n^2)  ((n-1)n) / 2 해서 

</details>

<details><summary>2025 08 05</summary>



# count 정렬

안정정렬 위해 뒤에서부터 정렬

안정정렬? 

동일 숫자 여러 개 존재하는 경우, 이 숫자들의 순서를 보






</details>


<details><summary>20250807</summary>

**2차원 리스트**

1. 주어진 2차원 리스트 입력 받기

[list(map(int, input().split())) for _ in range(N) ]  : 리스트 속 리스트. N 줄 입력받음

>> N행 짜리, 한 줄당 입력받은 개수 열 행렬이 입력됨.

2. 완전 검색
행당 모든 열 검색
for i in range(N):
   for j in range(M):
      arr[i][j]

열당 모든 행 검색
for j in range(N):
   for i in range(N):
      arr[i][j]


대각선 
for i in range(N):
   arr[i][i]
   arr[i][N-1-i]

지그재그
for i in range(N):
   for j in range(M):
      arr[i][j+(M-1-2j)*(N%2)]


3. 여러 가지
델타(방향과 변화량)
방향 설정 [[][][][]]
크기 설정 for c in range(1,k+1):
            ni, nj = c*di, c*dj
   ( range 로 설정해야 기준 지점으로부터 한 칸 두 칸 ... k칸까지 봄. range 없으면 지정 거리 위치만 )

4. 문제 유형
 
- 색칠하기

(주어진 행렬을 다 담지 않고, 줄별로 변수만 가져와서 바로바로 치워버림)
카운트를 담을 0 행렬을 생성. [[0] * N for _ in range(N)]

특정 구간에 해당하는 칸에 색칠 (숫자 더함)

주어지는 리스트들을 한 줄씩 한 줄씩 변수에 담고 아까 생성한 0행렬 색칠함.

- 정사각형 내부 정사각형

큰 정사각형 내부에서 작은 정사각형이 들어갈 수 있는 범위 

4중 for 문 >> 작은 정사각형의 시작점이 가능한 범위 (행과 열) range(N-M+1)
/ 작은 정사각형의 크기 range(i, i+M) 하고 해당하는 칸에 숫자를 할당. 반복문마다 1씩 커지게

내가 원하는 인덱스의 끝값을 생각하기..

N짜리 길이에 M 길이 들어가는 생각 하면 .. 마지막 인덱스는 N-1 이라 N-M에서 시작하면 딱 M

근데  range는 마지막 값 빼니까 range(N-M+1)로 되는 것. 


- 어디에 단어?

딱 맞는 칸의 개수 찾기 

가로(행) 별로 찾고 세로(열) 별로 찾고 총 2회

한 행에서 모든 열 탐색, 1이면 count에 1 더함 or 0이면 이전 count=K 이면 result 1추가 아니면 count 초기화

마지막에 count == K 면 result 1 추가











</details>

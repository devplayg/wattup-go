# Draft

## Ch 

Go 소개 
- Go는 누가/언제/어디서 만들었고, 어디서 많이 씁니다.
- Ken Thompson
- Rob Pike
- Robert Grizmer(x)

Hello world
- Hello world 실행부터 해봅시다.
- 구조는 이렇습니다.


## Ch 

Go 설치
- Go 설치는 이렇게 합니다.
    - Windows/Linux/Mac

통합개발환경(IDE) 설치
- 개발을 위한 도구는 Goland를 추천합니다.

코딩팁
- 함수의 길이는 최대한 짧게 작성하는 
- 함수나 변수명은 되도록 누구나 보면 알 수 있도록 작성하는

## Ch

변수 선언
- 길게, 짧게, 한줄에 

데이터 타입
- 이제 본격적으로 Go에 대해 상세하게 알아가봅니다.

일반 타입
- 일반 타입은 이런 유형들이 있습니다.
    - 숫자
    - 문자
    - 상수
    - 열거형
    - 배열

특수 타입
- 약간 특수한 타입들이 몇 가지 있습니다.
    - Rune
    - 유니코드 & UTF-8

유용한 구조체(?)
- 유용한 구조체가 있어요.

    - 슬라이스 (reference type)
    - 맵  (reference type)
    - 정렬

함수
- 리턴을 여러개 받을 수 있어요.
- 클로저
- defer
- 패닉/복구
- 인터페이스

에러 처리
- errors as values 개념입니다.
    - Go 에서는 error 를 변수 개념으로 봅니다.

구조체
- 구조체도 만들 수 있습니다.
- 구조체에 함수를 달 수 있어요.
- reset(); *m = File{}
- 포인터
- 구조체 임베딩
- 구조체에 함수를 달기


## Ch 4

고루틴 & 채널
동기화
- wait
- ch 
압축
암호화


## Ch 5

단위테스트
벤치마킹


## Ch 3

입출력

출력함수

임력함수

문자열 입출력

정규식

파일 입출력


문자열 함수

정규식

파일 처리

JSON

HTTP

## Tips

문서화하기
readme


---
go module

#### 201
grpc
context
template
memory
reflection
C언어 연동
github
---

Keywords

    break     default      func    interface  select
    case      defer        go      map        struct
    chan      else         goto    package    switch
    const     fallthrough  if      range      type
    continue  for          import  return     var


go by example

Hello World
Values
Variables
Constants
For
If/Else
Switch
Arrays
Slices
Maps
Range
Functions
Multiple Return Values
Variadic Functions
Closures
Recursion
Pointers
Structs
Methods
Interfaces
Errors
Goroutines
Channels
Channel Buffering
Channel Synchronization
Channel Directions
Select
Timeouts
Non-Blocking Channel Operations
Closing Channels
Range over Channels
Timers
Tickers
Worker Pools
WaitGroups
Rate Limiting
Atomic Counters
Mutexes
Stateful Goroutines
Sorting
Sorting by Functions
Panic
Defer
Collection Functions
String Functions
String Formatting
Regular Expressions
JSON
XML
Time
Epoch
Time Formatting / Parsing
Random Numbers
Number Parsing
URL Parsing
SHA1 Hashes
Base64 Encoding
Reading Files
Writing Files
Line Filters
File Paths
Directories
Temporary Files and Directories
Testing
Command-Line Arguments
Command-Line Flags
Command-Line Subcommands
Environment Variables
HTTP Clients
HTTP Servers
Context
Spawning Processes
Exec'ing Processes
Signals
Exit



- https://play.golang.org/
    레츠기릿
    - 친해져야할 것
    - https://golang.org/dl/    
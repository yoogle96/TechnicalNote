**자료형**
==========

작성자
------

[![tdm1223](https://avatars1.githubusercontent.com/u/21440957?s=100&v=4)](https://github.com/tdm1223)

자료형
------

-	컴퓨터 과학과 프로그래밍 언어에서 여러 종류의 데이터를 식별하는 분류이다.<sup>[1)](#ref1)</sup>
-	해당 자료형에 대해 가능한 값, 해당 자료형에서 수행을 마칠 수 있는 명령들, 데이터의 의미, 해당 자료형의 값을 저장하는 방식을 결정한다.

알고리즘 문제 풀이를 위한 C++과 JAVA의 자료형
---------------------------------------------

### C++의 자료형 (32비트 운영체제 기준)

| 구분   | 자료형                   | 크기   | 범위                                                                  |
|:------:|:------------------------:|:------:|:---------------------------------------------------------------------:|
| 문자형 |      (signed) char       | 1 byte |                              -128 ~ 127                               |
|        |      unsigned char       | 1 byte |                                0 ~ 255                                |
| 정수형 |           bool           | 1 byte |                                 0 ~ 1                                 |
|        |   (signed) short (int)   | 2 byte |                           -32,768 ~ 32,767                            |
|        |   unsigned short (int)   | 2 byte |                              0 ~ 65,535                               |
|        |       (signed) int       | 4 byte |                    -2,147,483,648 ~ 2,147,483,647                     |
|        |       unsigned int       | 4 byte |                           0 ~ 4,294,967,295                           |
|        |   (signed) long (int)    | 4 byte |                    -2,147,483,648 ~ 2,147,483,647                     |
|        |   unsigned long (int)    | 4 byte |                           0 ~ 4,294,967,295                           |
|        | (signed) long long (int) | 8 byte |        -9,223,372,036,854,775,808 ~ 9,223,372,036,854,775,807         |
|        | unsigned long long (int) | 8 byte |                    0 ~ 18,446,744,073,709,551,615                     |
| 실수형 |          float           | 4 byte |     3.4E-38(-3.4*10<sup>38</sup>) ~ 3.4E+38(3.4*10<sup>38</sup>\)     |
|        |          double          | 8 byte | 1.79E-308(-1.79*10<sup>308</sup>) ~ 1.79E+308(1.79*10<sup>308</sup>\) |

### JAVA의 자료형

| 구분   | 자료형  | 크기   | 범위                                                                  |
|:------:|:-------:|:------:|:---------------------------------------------------------------------:|
| 논리값 | boolean | 1 byte |                             true or false                             |
|  문자  |  char   | 2 byte |                               0 ~ 65535                               |
|  정수  |  byte   | 1 byte |                              -128 ~ 127                               |
|        |  short  | 2 byte |                           -32,768 ~ 32,767                            |
|        |   int   | 4 byte |                    -2,147,483,648 ~ 2,147,483,647                     |
|        |  long   | 8 byte |        -9,223,372,036,854,775,808 ~ 9,223,372,036,854,775,807         |
|  실수  |  float  | 4 byte |     3.4E-38(-3.4*10<sup>38</sup>) ~ 3.4E+38(3.4*10<sup>38</sup>\)     |
|        | double  | 8 byte | 1.79E-308(-1.79*10<sup>308</sup>) ~ 1.79E+308(1.79*10<sup>308</sup>\) |

각주
----

<a id="ref1">

1.	[Wiki](https://ko.wikipedia.org/wiki/%EC%9E%90%EB%A3%8C%ED%98%95)

</a>

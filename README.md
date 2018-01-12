# 더 이상 지원하지 않습니다. BOJ API가 출시되면 출시될 새 버전을 기다려주세요

# [Baekjoon Online Judge](http://www.acmicpc.net/) Submit Tool

## Tool 사용법

- python submit.py 파일이름
- python submit.py 문제번호 파일이름

### 예제

	python submit.py 1920.cpp
	python submit.py 1920 1920.cpp
	
### 주의 사항
- 확장자로 어떤 언어인지 판별합니다.
- 문제번호를 입력하지 않고 제출할 때는  문제번호.확장자 형식이어야 합니다. 예) 1920.cpp, 1000.py

### python을 치기 귀찮다면…

아래와 같이 해도 제출은 됩니다.

	./submit.py 1920 1920.cpp
	
그런데, .py도 치기 귀찮다면

	mv submit.py submit
	./submit 1920 1920.cpp
	
이렇게 하면 됩니다.



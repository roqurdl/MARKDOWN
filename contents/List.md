```
1. 나무
	1.1. 잎
		1.1.1. 엽록체
	1.2. 가지
	1.3. 뿌리
```

위와 같은 하위 항목을 만들 때 사용한다.

방법은  다음과 같이 2가지 방식이 있다.

+ 기호로 표기
+ 숫자로 표기

1. 기호로 표기하는 방법

```
* 나무
	* 기둥
		* 가지
+ 나무
	+ 기둥
		+ 가지
- 나무
- 기둥
- 가지

```

위와 같이 사용하며 각각 \*, \+, \- 를 사용하며 다음과 같이 표시된다.

* 나무
	* 기둥
		* 가지
+ 나무
	+ 기둥
		+ 가지
- 나무
- 기둥
- 가지

tab키를 통해서 하위 항목

---

2. 숫자로 표기하는 방법

```
1. 나무
2. 기둥
3. 가지
```
'1.' 다음에 띄어쓰기를 한 번 하고 내용을 쓰기만 하면 된다.

1. 나무
2. 기둥
3. 가지

\※ 주의사항
+ 숫자 뒤에 \.을 붙이는 것으로 리스트는 실행된다.

예를 들어 ```2022.08.01``` 와 같이 날짜를 입력한다고 하면 다음과 같이 리스트가 되어버린다.
2022. 08. 01
2023. 08. 01

이럴 때는 \\ 를 사용하여 ```2022\. 08. 01 ```로 표기하면 문제 없이 처리된다.

이는 [특수문자](/contents/특수문자.md)를 처리하는 방식이다.
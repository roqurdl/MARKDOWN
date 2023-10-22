코드 상자는 마크다운 페이지에 메모장을 붙이는 것으로 생각하면 편하다.
***
```
이게 바로 코드 상자
```
***
해당 기능을 사용하게 되면 생김도 달라지지만 내가 입력하는 모든 값이 텍스트화 되어 나타난다는 것이다. 이미 '\\'를 사용하여 [특수문자](/contents/특수문자.md)들을 텍스트화하여 입력하는 방법도 존재하지만 코드 상자를 쓰는 사용하는 경우 다음과 같은 효과를 가져올 수 있다.

1. 시각적인 효과
특정 내용을 강조하거나 특별하게 본문과 분리하여 쓰고 싶은 경우 해당 상자를 사용하여 강조할 수 있다. 

2.  코드를 작성
코드 상자의 주된 기능이다. 다음과 같이 html을 입력하는 경우 해당 테그가 노출되게 되는데 이를 방지해준다. 

```
<img src=0>
<hr>
```  

<img src=0>
<hr>

또한 Git hub에서는  \`\`\`이 시작되는 위치에 사용하는 언어를 선언하여 문법을 강조할 수 있는 기능이 내재되어 있다.

````
```java
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```
````

```java
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```

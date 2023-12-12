### refence type(참조 타입)
✅ 기본 타입 8개 빼고 모두 다!

(기본 타입 : byte, char, short, int, long, float, double, boolean)

😈 옛날에 배울 때 대박 헷갈렸던 참조타입 저장 😈

#### String
```java
String c;
c = "spring";
```
instance가 저장되는 공간은 따로있고 그 주소를 변수가 따로 저장하고 있음


#### Array

```java
int[] c = {3, 4, 5};
int [] d = c;
```
<br />

근데! 여기서 c[2] = 55; 로 값을 변경해버려

```java
System.out.println(c[2]); //55
System.out.println(d[2]); 
```
    
d[2]는? 55 -> 인스턴스 값이 바뀌니까
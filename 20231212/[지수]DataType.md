# DataType
### primitive type (기본타입)

기본타입은 8가지가 있다
int, long, float, blooean, char, vyte, short, double
```
int a; //변수 선언
a = 3; //데이터 타입에 맞는 값만 대입 가능
//a = 3.14; (에러) 변수의 타입에 맞는 값만 넣을 수 있다
```
기본 타입은 선언이 되면 memory에 저장공간이 생기고 그 안에 값이 바로 저장된다

### reference type (참조타입)
참조타입은 기본타입을 제외한 모두 다
```
String a; //참조타입
String b; //참조타입

int c; //기본타입
int[] d; //참조타입
```
참조타입이 선언이 되면 memory에 instance가 생김
instance 안에 선언한 값이 저장됨
그리고 변수안에는 instance의 주소값이 저장됨

```
int[] c = {1,2,3};
int[] b = c;

System.out.println(c[1]); // 2
System.out.println(d[1]); //2

c[2] = 55;

System.out.println(c[2]); //55
System.out.println(d[2]); //55
```
reference type은 값 자체를 저장하는 것이 아니라 값을 저장한 주소값을 저장하기 때문에
<br/>
원래의 값인 c의 값이 변경되면 d의 값도 변경되는 것이다
(사실 변경되는 건 아님, d의 값 안에 있는 참조값은 변하지 않았음)

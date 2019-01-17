# 2장 : 객체의 생성과 파괴 

참석자 : 신은 민지 다영 준영 
정리 : 준영 


## ITEM 01 생성자 대신 정적 팩터리 메서드를 고려하라 

정적 팩토리 메서드란, 다음과 같이 해당 클래스의 인스턴스를 반환하는 static 메소드를 말한다. 

```java
public static Boolean valueOf(boolean b){
    return b ? Boolean.True: Boolean.False; 
}
```

### 장점 

1. 이름을 가질 수 있다. 
    * 정적 팩토리는 이름만 잘 지으면 반환될 객체의 특성을 쉽게 묘사할 수 있다.
    * 하나의 시그니처로는 생성자를 하나만 만들 수 있다. 

# Design-Patterns
## Creational Patterns
#### 객체를 생성하거나 조합해 캡슐화하는 방법에 대한 패턴
### ◽ Singleton

### ◽ Factory Method

### ◽ Abstract Factory
* 관련된 여러 객체를 생성하는 인터페이스를 클라이언트에게 제공함으로써, 객체 생성 과정을 캡슐화하는 패턴</br>
  * 장점: 관련된 여러 종류의 객체를 '일관된' 방식으로 생성하는 경우 유용하며, 해당 패턴을 사용하면 개방-폐쇄 원칙, 단일 책임 원칙을 준수할 수 있음
  * 단점: 구현체가 추가될 때마다 팩토리 클래스를 새로 작성해야 함
    
### ◽ Builder Pattern
* 생성자만 사용하여 객체를 생성할 때 발생할 수 있는 문제를 해결하기 위한 패턴. 필수 매개변수는 생성자를 통해, 선택적 매개변수는 메소드 체이닝을 통해 해당 클래스에게 제공하여 객체를 생성함
  * 장점: 매개변수가 많을 경우 가독성 향상, setter가 없어 불변 객체 생성 가능, 필요한 데이터만 설정 가능, 유연성 확보
  * 단점: 남용시 코드 복잡성 증가, 필수 매개변수가 모두 설정되었는지에 대한 검증 로직 필요

 </br>
 
## Structural Patterns
#### 기존 객체를 조합해 더 큰 단위의 구조를 생성하는 패턴
### ◽ Decorator

### ◽ Composite


 </br>

## Behavioral Patterns
#### 객체 간의 책임 분배나 알고리즘을 통해 목표를 달성하는 방법을 제시하는 패턴
### ◽ State

### ◽ Command

### ◽ Observer

### ◽ Template Method

 </br>

#### 🔎 references
JAVA 객체지향 디자인패턴 - 정인상, 채흥석 저 </br> 
Python in Practice - Mark Summerfield 저 </br>
코딩으로 학습하는 GoF의 디자인 패턴 - 백기선

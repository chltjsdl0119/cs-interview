# cs-interview


<details>

<summary><h2>Java</h2></summary>

## [OOP 기초](https://github.com/chltjsdl0119/cs-interview/blob/main/Java/OOP%20기초.md)

### 1. 클래스, 인스턴스, 객체의 차이점은 무엇인가요?
### 2. 객체지향 프로그래밍(OOP)의 4대 원칙을 설명해주세요.
### 3. 절차지향 프로그래밍과 객체지향 프로그래밍의 차이점은 무엇인가요?
### 4. SOLID 원칙이란 무엇이고, 각각에 대해 설명해주세요.
### 5. SRP(단일 책임 원칙)를 위반하는 예시와 이를 리팩토링하는 방법을 설명해주세요.
### 6. OCP(개방-폐쇄 원칙)를 실제 코드에 어떻게 적용하나요?
### 7. LSP(리스코프 치환 원칙)를 위반하는 대표적인 예시는 무엇인가요?
### 8. ISP(인터페이스 분리 원칙)와 DIP(의존성 역전 원칙)의 차이를 설명해주세요.
### 9. DI(의존성 주입)란 무엇이고, 왜 사용하나요?

---

## 상속 & 조합

### 1. 상속과 조합은 각각 무엇이고 어떤 상황에서 사용하나요?
### 2. 상속이 갖는 문제점은 무엇이고 이를 어떻게 해결할 수 있나요?
### 3. Java에서 다중 상속이 불가능한 이유는 무엇인가요? (Diamond Problem)
### 4. final 클래스와 final 메서드는 왜 사용하나요?
### 5. super 키워드와 this 키워드의 차이를 설명해주세요.
### 6. 상속 계층이 깊어질수록 발생하는 문제점은 무엇인가요?
### 7. 조합(Composition)을 상속보다 선호하는 이유를 예시와 함께 설명해주세요.

---

## 다형성

### 1. Java에서 다형성을 구현하는 방법은 무엇이 있나요?
### 2. Overriding의 조건은 무엇인가요?
### 3. Method overriding과 overloading의 차이점은 무엇인가요?
### 4. 다형성은 무엇이고, 사용했을 때 어떤 이점을 얻을 수 있나요?
### 5. 동적 디스패치(Dynamic Dispatch)란 무엇인가요?
### 6. 공변 반환 타입(Covariant Return Type)이란 무엇인가요?
### 7. Java에서 정적 메서드는 왜 오버라이딩이 안 되나요?
### 8. instanceof 연산자와 패턴 매칭(Java 16+)을 설명해주세요.
### 9. sealed class(Java 17+)는 무엇이고, 다형성과 어떤 관계가 있나요?

---

## 캡슐화

### 1. 클래스의 변수를 private으로 설정하고 getter/setter를 사용하는 이유는 무엇인가요?
### 2. Java에서 접근 제어자(public, protected, default, private)에 대해 설명해주세요.
### 3. getter/setter를 무분별하게 사용했을 때 발생할 수 있는 문제점은 무엇인가요?
### 4. 불변 객체(Immutable Object)와 캡슐화의 관계를 설명해주세요.
### 5. Java record는 캡슐화 측면에서 어떤 특징을 갖나요?
### 6. Tell, Don't Ask 원칙이란 무엇이고, 캡슐화와 어떤 관계인가요?

---

## 추상화

### 1. 강한 결합과 느슨한 결합의 차이를 설명해주세요.
### 2. 추상 클래스와 인터페이스는 어떤 상황에서 사용하나요?
### 3. 추상 클래스와 인터페이스의 차이를 설명해주세요.
### 4. Java 8 이후 인터페이스에 default 메서드가 추가된 이유는 무엇인가요?
### 5. 인터페이스와 추상 클래스 중 어느 것을 선택해야 할지 기준을 설명해주세요.
### 6. 의존성 역전(DIP)과 추상화의 관계를 설명해주세요.
### 7. Java에서 marker interface(마커 인터페이스)란 무엇이고 어떤 역할을 하나요?

---

## JVM

### 1. Java 파일이 실행되는 과정을 설명해주세요.
### 2. 클래스와 인스턴스는 JVM 내에서 어떻게 동작하나요?
### 3. JVM이란 무엇이고 왜 사용하나요?
### 4. JRE, JDK, JVM의 관계를 설명해주세요.
### 5. JVM의 구조에 대해 설명해주세요.
### 6. JVM의 Runtime Data Area에 대해 설명해주세요.
### 7. JVM의 ClassLoader에 대해 설명해주세요.
### 8. JIT(Just-In-Time) 컴파일러란 무엇이고 어떻게 동작하나요?
### 9. Java와 C/C++의 메모리 관리 방식 차이를 설명해주세요.
### 10. StackOverflowError와 OutOfMemoryError의 차이는 무엇인가요?
### 11. Metaspace란 무엇이고 PermGen과의 차이는 무엇인가요?
### 12. JVM 튜닝 옵션(-Xms, -Xmx 등)을 설명해주세요.

---

## GC (가비지 컬렉션)

### 1. GC가 무엇이고 언제 발생하는지 설명해주세요.
### 2. Stop-the-World 이벤트란 무엇인지 설명해주세요.
### 3. Minor GC와 Major GC에 대해 설명해주세요.
### 4. Young Generation과 Old Generation의 차이를 설명해주세요.
### 5. GC 알고리즘의 종류(Mark-Sweep, Mark-Compact, Copying)를 설명해주세요.
### 6. G1GC, ZGC, Shenandoah GC의 차이를 설명해주세요.
### 7. GC 루트(GC Root)란 무엇인가요?
### 8. 메모리 누수(Memory Leak)가 Java에서 발생할 수 있는 상황은 어떤 것이 있나요?
### 9. WeakReference, SoftReference, PhantomReference의 차이를 설명해주세요.

---

## 타입 시스템

### 1. 제네릭이란 무엇이며 언제 사용하나요?
### 2. 제네릭에서 와일드카드(?, extends, super)의 차이를 설명해주세요.
### 3. 타입 소거(Type Erasure)란 무엇이고 어떤 한계가 있나요?
### 4. PECS(Producer Extends Consumer Super) 원칙이란 무엇인가요?
### 5. 제네릭 메서드와 제네릭 클래스의 차이는 무엇인가요?
### 6. Enum은 무엇이며 어떤 상황에 사용하나요?
### 7. Enum에 메서드와 필드를 추가하는 방법과 그 활용 사례를 설명해주세요.
### 8. EnumSet과 EnumMap을 사용하는 이유는 무엇인가요?
### 9. Varargs는 무엇이며 언제 사용하나요?

---

## 불변성 & 복사

### 1. 가변과 불변의 차이는 무엇인가요?
### 2. 불변 객체를 만드는 방법을 설명해주세요.
### 3. String이 불변 객체인 이유와 그 장점을 설명해주세요.
### 4. String pool(문자열 상수 풀)이란 무엇인가요?
### 5. String, StringBuilder, StringBuffer의 차이점은 무엇인가요?
### 6. 깊은 복사와 얕은 복사의 차이점은 무엇인가요?
### 7. 방어적 복사는 무엇이고 왜 필요한가요?
### 8. unmodifiable 자료형과 copyOf의 차이점은 무엇인가요?
### 9. Java record는 불변 객체를 어떻게 보장하나요?

---

## 동일성 & 동등성

### 1. 동등성과 동일성의 차이에 대해 설명해주세요.
### 2. == 연산자와 equals() 메서드의 차이는 무엇인가요?
### 3. equals()와 hashCode()는 언제 재정의하고, 왜 항상 같이 재정의해야 하나요?
### 4. equals()만 재정의하고 hashCode()를 재정의하지 않으면 어떤 문제가 발생하나요?
### 5. Objects.equals()를 사용하는 이유는 무엇인가요?
### 6. HashSet에서 커스텀 객체를 사용할 때 주의사항은 무엇인가요?

---

## 예외 처리

### 1. 예외의 종류(Checked, Unchecked)와 각각의 특징을 설명해주세요.
### 2. Error와 Exception의 차이는 무엇인가요?
### 3. Checked Exception과 Unchecked Exception 중 어느 것을 언제 사용해야 하나요?
### 4. try-catch-finally와 try-with-resources의 차이를 설명해주세요.
### 5. 예외를 잡아서 무시하면(catch 블록 비움) 어떤 문제가 발생하나요?
### 6. 커스텀 예외를 만들 때 고려해야 할 사항은 무엇인가요?
### 7. 예외 체이닝(Exception Chaining)이란 무엇인가요?
### 8. 예외 처리 전략(로깅, 변환, 전파)에 대해 설명해주세요.

---

## 리소스 관리 & 직렬화

### 1. Java에서 어떤 경우에 리소스 반납을 해야 하나요?
### 2. try-with-resources는 어떻게 사용하나요?
### 3. AutoCloseable과 Closeable의 차이는 무엇인가요?
### 4. ThreadLocal을 사용할 때 리소스 누수가 발생할 수 있는 상황은 무엇인가요?
### 5. Serializable 인터페이스는 어떤 역할을 하나요?
### 6. serialVersionUID는 왜 선언해야 하나요?
### 7. transient 키워드는 무엇이고 언제 사용하나요?
### 8. Java 직렬화의 단점과 보안 취약점을 설명해주세요.
### 9. JSON 직렬화(Jackson, Gson)와 Java 기본 직렬화의 차이를 설명해주세요.

---

## Java 8+ 핵심 기능

### 1. default 메서드는 무엇이고, 왜 사용하나요?
### 2. Optional이란 무엇이며, 어떤 문제를 해결하기 위해 도입되었나요?
### 3. 자바에서 null을 안전하게 다루는 방법을 설명해주세요.
### 4. Optional을 사용할 때 주의해야 할 부분은 무엇인가요?
### 5. Optional.orElse()와 Optional.orElseGet()의 차이를 설명해주세요.
### 6. Java Stream API에 대해 소개해주세요.
### 7. 스트림과 for-loop의 차이점을 설명해주세요.
### 8. Stream API 사용 시 성능 고려사항을 설명해주세요.
### 9. parallelStream()은 언제 사용해야 하고 언제 사용하면 안 되나요?
### 10. 함수형 인터페이스란 무엇이고 어떻게 사용하나요?
### 11. Java 기본 함수형 인터페이스(Function, Predicate, Consumer, Supplier)의 용도를 설명해주세요.
### 12. 람다와 익명 클래스의 차이점과 장단점은 무엇인가요?
### 13. @FunctionalInterface 어노테이션을 사용하는 이유는 무엇인가요?
### 14. 메서드 참조(Method Reference)의 종류와 사용 방법을 설명해주세요.
### 15. Collector와 collect() 메서드의 동작 방식을 설명해주세요.
### 16. CompletableFuture와 Future의 차이를 설명해주세요.
### 17. record, sealed class, pattern matching 등 Java 14~21의 주요 변화를 설명해주세요.

---

## 컬렉션 프레임워크

### 1. JCF(Java Collections Framework)란 무엇인가요?
### 2. Array와 List의 차이점은 무엇인가요?
### 3. ArrayList는 어떻게 동작하나요?
### 4. ArrayList의 11번째 element를 add할 때 어떤 일이 일어나나요?
### 5. ArrayList와 LinkedList의 시간복잡도 차이를 설명해주세요.
### 6. ArrayList의 indexOf() 사용 시 주의사항은 무엇인가요?
### 7. Stack 대신 ArrayDeque 사용을 제안하는 이유는 무엇인가요?
### 8. Set과 List의 차이점은 무엇인가요?
### 9. HashSet, LinkedHashSet, TreeSet의 차이를 설명해주세요.
### 10. HashMap에서 Hash 충돌이 발생하면 어떻게 되나요?
### 11. Java 8에서 HashMap이 어떻게 개선되었나요?
### 12. HashMap과 TreeMap의 차이점은 무엇인가요?
### 13. HashMap과 LinkedHashMap의 차이는 무엇인가요?
### 14. ConcurrentHashMap은 HashMap과 어떻게 다른가요?
### 15. Collections.synchronizedMap과 ConcurrentHashMap의 차이는 무엇인가요?
### 16. PriorityQueue는 어떻게 동작하나요?
### 17. 불변 컬렉션(List.of(), Map.of())을 사용하는 이유는 무엇인가요?
### 18. fail-fast와 fail-safe 이터레이터의 차이를 설명해주세요.

---

## 동시성 & 멀티스레딩

### 1. Thread와 Process의 차이를 설명해주세요.
### 2. Java에서 스레드를 생성하는 방법을 설명해주세요.
### 3. synchronized 키워드는 어떻게 동작하나요?
### 4. volatile 키워드는 무엇이고 언제 사용하나요?
### 5. 교착상태(Deadlock)란 무엇이고, 발생 조건과 해결 방법은 무엇인가요?
### 6. Race Condition이란 무엇이고 어떻게 방지하나요?
### 7. ThreadLocal이란 무엇이고 언제 사용하나요?
### 8. ExecutorService와 ThreadPoolExecutor를 설명해주세요.
### 9. ReentrantLock과 synchronized의 차이는 무엇인가요?
### 10. AtomicInteger 같은 Atomic 클래스는 어떻게 동작하나요?
### 11. happens-before 관계란 무엇인가요?
### 12. Java 21의 Virtual Thread(Project Loom)를 설명해주세요.

</details>

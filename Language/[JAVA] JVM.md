# JVM

### Java Virtual Machine

### 실행과정
```
자바 컴파일러가 자바 소스코드(.java)를 읽어들여 자바 바이트코드(.class)로 변환
클래스 로더를 통해 클래스 파일들을 JVM으로 로딩
로딩된 클래스파일들은 Execute Engine을 통해 해석
해석된 바이트코드는 Runtime Data Areas에 배치됭 실질적인 수행
이러한 실행과정 속에서 JVM은 필용 따라 Thread Synchronization과 GC같은 관리작업 수행
```

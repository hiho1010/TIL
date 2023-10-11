# Java : 이것이 자바다
## 자바 설치 : oracle SE JDK 17
### 자바에서 변수값 출력하는 방법
+ 콘솔로 변수값 출력하기
  + `System.out,println();` : 괄호 안에 내용을 출력하고 행을 바꾼다. printf를 사용하는 format 문자열도 존재한다.
+ 키보드 입력값을 변수에 저장하기
  + `Scanner scanner = new Scanner(System.in);` : Scanner라는 객체를 생성하여 scanner라는 변수에 할당한다.
  + 그리고 다음과 같이 `scanner.nextLine();`을 사용하여 String 변수에 저장할 수 있다.
  + `String inputData = scanner.nextLine();`
    + `scanner.nextLine()`는  `Enter`가 입력되기 전까지 blocking 상태가 된다.



# Java에서 쓰레드는 운영체제에서의 쓰레드와는 다른 차원
### 운영체제에서 자바는 `미들웨어`라고(혹은 플랫폼) 생각하라했다.
+ 직접 쓰레드를 하거나
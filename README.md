# java-lotto-precourse

### 입력 부분 구현
  * 로또 구입 금액 입력
    * 입력받은 값이 숫자가 아니면 예외 처리
    * 입력받은 값이 음수이면 예외 처리
    * 입력받은 값이 0 이면 예외 처리
    * 1,000원 단위로 입력 받으며 1,000원으로 나누어 떨어지지 않는 경우 예외 처리
  * 당첨 번호 입력
    * 쉼표를 기준으로 구분한 값이 1 ~ 45까지의 수가 아니면 예외 처리
    * 로또 번호가 6개가 아니면 예외 처리
    * 로또 번호가 중복된 숫자면 예외 처리
  * 보너스 번호 입력

### 로또 당첨 기준 enum으로 처리

### 로또 당첨 로직 구현

### 로또 수익률 로직 구현

### 출력 부분 구현
  * 발행한 로또 수량 및 번호 출력
    * 로또 번호는 오름차순으로 정렬
  * 당첨 내역 출력
  * 수익률 출력
    * 소수점 둘째 자리에서 반올림한다.
***

### 예외 사항 처리 
  * 예외 상황 시 에러 문구를 출력해야 한다. 단, 에러 문구는 "[ERROR]"로 시작해야 한다.
    * ex) [ERROR] 로또 번호는 1부터 45 사이의 숫자여야 합니다.
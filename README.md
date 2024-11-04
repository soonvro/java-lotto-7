# java-lotto-precourse

## 개요
로또 구매 금액을 입력하면 자동으로 로또를 발매하여 입력받은 당첨 번호를 이용해 수익률을 계산하는 로또 발매기 입니다.

## 기능 목록

### 1. 구입 금액 입력 받기
-[x] 금액은 1,000원 단위로 입력 받는다.
-[x] 금액이 1,000으로 나누어 떨어지지 않으면 예외 처리한다.
-[x] 금액이 0 이하이면 예외 처리한다.
-[ ] 예외 처리 시 에러 메시지를 출력하고 다시 입력 받는다.

### 2. 로또 발매
-[x] 구입 금액에 따라 1,000원 당 한 장의 로또를 발매한다.
-[x] 로또 번호는 1~45 사이의 숫자 중 6개를 랜덤으로 발매한다.

### 3. 로또 발매 정보 출력
-[x] 발매된 로또 수량과 각각의 로또 번호를 출력한다.
-[x] 로또 번호는 오름차순으로 정렬하여 출력한다.

### 4. 당첨 번호 입력 받기
-[x] 쉼표로 구분된 6개의 숫자를 입력 받는다.
-[x] 숫자가 1~45 사이의 6개의 숫자가 아니거나 중복된 숫자가 입력되면 예외 처리한다.
-[x] 쉼표와 숫자 이외의 문자가 입력되면 예외 처리한다.
-[ ] 예외 처리 시 에러 메시지를 출력하고 다시 입력 받는다.

### 5. 보너스 번호 입력 받기
-[ ] 1개의 숫자를 입력 받는다.
-[ ] 숫자가 1~45 사이의 숫자가 아니면 예외 처리한다.
-[ ] 숫자 이외의 문자가 입력되면 예외 처리한다.
-[ ] 예외 처리 시 에러 메시지를 출력하고 다시 입력 받는다.

### 6. 당첨 결과 계산
-[ ] 당첨 번호와 보너스 번호를 이용해 로또 당첨 결과를 계산한다.
    - 1등: 6개 번호 일치 / 2,000,000,000원
    - 2등: 5개 번호 + 보너스 번호 일치 / 30,000,000원
    - 3등: 5개 번호 일치 / 1,500,000원
    - 4등: 4개 번호 일치 / 50,000원
    - 5등: 3개 번호 일치 / 5,000원

### 7. 수익률 계산
-[ ] 로또 구매 금액과 당첨 금액을 이용해 수익률을 계산한다.
-[ ] 수익률은 소수점 둘째 자리에서 반올림한다.

### 8. 결과 출력
-[ ] 당첨 통계, 수익률을 출력한다.

### 9. 예외 처리
-[ ] 예외 상황 시 에러 문구를 출력한다. 에러 문구는 "[ERROR]"로 시작한다.
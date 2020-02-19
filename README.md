# java-lotto
로또 미션 진행을 위한 저장소

## Todos

- [ ] 로또 구입 금액을 입력하면 구입 금액에 해당하는 로또를 발급해야 한다.
  - [ ] 금액을 입력 받아야 한다.
    - [x] 금액을 생성한다.
        - [x] 금액은 정수이어야 한다.
    - [x] 구입 금액은 1000원 단위여야한다.
    - [x] 구입 금액은 0이거나 음수 일 수 없다.
    - [x] 로또의 장 수를 계산한다. 
  - [x] 로또를 생성한다.//1
    - [x] 로또는 6개의 로또숫자로 구성 되어있다.
      - [x] 로또 숫자는 1 에서 45 사이의 숫자를 가져야 한다.
      - [x] 로또 숫자는 중복이 되면 안된다.
- [ ] 몇 개의 로또를 구매하였는지 출력한다.
- [x] 각 로또 번호를 출력한다.
- [ ] 지난 주 당첨 번호를 입력 받은 후, 보너스 볼을 입력받는다.//2
  - [x] 당첨 번호는 중복 되서는 안된다.
  - [x] 정수가 아닌 값이 들어면 안된다.
  - [x] 총 6개를 가져야 한다.
  - [x] 1에서 45 사이의 숫자를 가져야 한다.
- [ ] 당첨 통계를 출력한다.//3
  - [ ] 일치 개수에 따라 결과를 출력한다.
    - [ ] 5개의 일치 경우 2등인지 3등인지 구별 해야한다.
  - [ ] 등수에 맞는 금액을 지급한다.
  - [ ] 수익률을 계산한다.

## Exceptions
# kotlin-racingcar-precourse

## 구현할 기능 목록

1. 자동차 이름 입력 기능

- 자동차의 이름을 쉼표(,)로 구분하여 입력
- 이름은 5자 이하의 문자만 허용

2. 시도 횟수 입력 기능

- 몇 번의 라운드를 진행할지 숫자를 입력
- 숫자가 아닌 입력이 들어오면 예외 처리를 통해 올바른 입력을 요구

3. 자동차 이동 조건 결정 기능

- 각 자동차는 무작위 숫자(0-9)를 받아서 전진할지 결정
- 무작위 값이 4 이상인 경우 자동차가 전진

4. 자동차 이동 기능

- 각 자동차의 전진 횟수를 나타내는 moveCount 값을 관리

- 전진 조건을 만족할 때마다 moveCount을 1씩 증가

5. 경기 진행 및 결과 출력 기능

- 지정된 횟수만큼 모든 자동차의 이동을 반복

- 각 경기가 끝날 때마다 모든 자동차의 현재 위치를 출력

6. 우승자 결정 기능

- 모든 라운드가 끝난 후, 가장 멀리 이동한 자동차를 우승자로 결정

- 이동 거리가 같은 자동차가 여러 대 있을 경우 공동 우승자로 처리

7. 예외 처리 기능

- 잘못된 값을 입력했을 때 적절한 예외를 발생시키고 오류 메시지를 출력
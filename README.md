# java-racingcar-precourse

 ## MVC 패턴 적용 전
- [ ] 자동차 클래스 
  - 속성 - 이름(carName), 이동한 칸수(position)
  - 함수1 - 자동차 이름을 return하는 함수
  - 함수2 - 자동차가 이동한 칸 수를 return하는 함수
  - 함수3 - 이름 + 이동 칸 수를 출력하는 함수

- [ ] 경주 클래스
  - 함수1 - 사용자의 입력을 받고, 경주를 시작하는 함수
  - 함수2 - 시도할 횟수만큼 각 자동차의 이동을 진행하는 함수
  - 함수3 - 특정 자동차의 경주 1회 시도하는 함수 
    - 함수3-1 - 무작위 값을 돌려 전진 여부를 결정하는 함수
    - 함수3-2 - 전진 여부에 따라 해당 자동차 이동 기록하는 함수
    - 함수3-3 - 실행 결과 출력하는 함수
  - 함수4 - 경주가 완료된 이후 우승자를 계산하는 함수
  - 함수5 - 우승자를 출력하는 함수
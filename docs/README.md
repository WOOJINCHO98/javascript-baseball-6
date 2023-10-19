# 구현할 기능 목록

### 게임 초기화 

게임 시작 문구 출력한다: "숫자 야구 게임을 시작합니다."

컴퓨터(상대)에 임의의 3자리 숫자를 생성하여 게임을 초기화한다.

---

### 플레이어로부터의 입력 

플레이어에게 3자리 숫자를 입력하라는 메시지를 표시한다.

입력이 고유한 숫자(1-9)를 포함하는 3자리 숫자인지 확인한다.
잘못된 입력에 대한 예외를 처리한다.

---

### 추측 비교 

플레이어에게 받은 입력을 컴퓨터가 생성한 난수와 비교한다.

같은 포지션에 같은 숫자가 있는지, 다른 포지션에서 같은 숫자가 있는지를 확인하여 각각의 수가 스트라이크인지 볼인지 확인한다.

플레이어가 세 숫자를 모두 추측에 실패했는지 성공했는지를 확인한다.

---

### 결과 출력

결과를 출력한다.

스트라이크 및/또는 볼이 있는 경우 

"X 볼 Y 스트라이크"

일치하는 항목이 없다면 

"낫싱"

스트라이크가 3번 있다면 

"3개의 숫자를 모두 맞히셨습니다! 게임 종료"

---

### 게임 루프 

플레이어가 세 숫자를 모두 올바르게 추측할 때까지 계속 추측하도록 한다.

---

### 게임 종료 

추측에 성공한다면 플레이어에게 새 게임을 시작할 것인지 아니면 종료할 것인지 묻는다(1은 새 게임을 시작하고 2는 종료).

새 게임을 시작하거나 종료하기 위한 플레이어 입력을 처리한다.

---

### 예외 처리 

유효하지 않은 입력 (예: 숫자가 아닌 입력, 중복된 숫자가 포함된 입력 또는 유효한 범위를 벗어난 입력) 에 대해 throw 문을 사용해 예외를 발생시킨후 애플리케이션을 종료시킨다.

---

### 난수 생성 

고유한 숫자로 컴퓨터(상대)에게 무작위 3자리 숫자를 생성한다.

---


### 오류 처리 

유익한 오류 메시지를 통해 예상치 못한 오류를 적절하게 처리한다.

---

### 문서 

명확성과 유지 관리 용이성을 위해 코드에 주석과 문서를 추가한다.

---

### 테스트 

게임을 철저히 테스트하여 모든 기능이 예상대로 작동하는지 확인한다.

---
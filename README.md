# javascript-calculator-precourse

## 우아한 테크 코스 프리코스 - 1주차

1. **빈 문자열 처리 기능**:

    - 입력된 문자열이 비었을 경우, 결과는 0을 반환한다.

2. **기본 구분자(쉼표, 콜론)로 문자열 분리 기능**:

    - 입력된 문자열에서 쉼표(`,`)와 콜론(`:`)을 구분자로 사용하여 숫자를 분리한 후 합산한다.

3. **커스텀 구분자 지정 기능**:

    - 문자열이 "//"로 시작하고 "\n"이 있는 경우, 그 사이의 문자를 커스텀 구분자로 지정하고 이를 기준으로 숫자를 분리한다.
    - 예: "//;\n1;2;3"의 경우 세미콜론(`;`)을 구분자로 사용하여 숫자를 분리하고 합산한다.

4. **숫자 합산 기능**:

    - 구분자를 기준으로 분리된 문자열을 숫자로 변환한 후, 모든 숫자를 더해 결과를 반환한다.

5. **잘못된 입력 처리 기능**:

    - 입력된 문자열에 구분자 외의 잘못된 값이 포함된 경우, "[ERROR]"로 시작하는 에러 메시지를 출력하고 프로그램을 종료한다.

6. **결과 출력 기능**:
    - 계산된 덧셈 결과를 화면에 출력한다.

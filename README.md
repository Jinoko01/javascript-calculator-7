# javascript-calculator-precourse

## ✅ 체크포인트

- [x] Node.js 20.17.0 이상의 버전 설치
- [x] 문자열의 길이가 0인경우 바로 0 출력
- [x] 쉼표(,), 콜론(:)을 기본 구분자로 구분자를 관리하는 delimiters 배열에 추가
- [x] 구분자로 문자열을 나누는 splitByDelimiter 함수 구현
  - reg 배열 내에 들어있는 문자열을 구분하는 정규식 작성
  - 정규식을 활용하여 구분자를 기준으로 문자열을 나눠서 numbers 배열에 저장
- [x] 커스텀 구분자를 추가하는 함수 구현
  - "//"와 "\n" 사이에 위치하는 문자를 인식하는 정규식 작성
  - 정규식을 활용하여 reg 배열에 추가
- [x] numbers 배열에 존재하는 모든 숫자를 덧셈하는 add 함수 구현
- [ ] 잘못된 값을 입력할 경우 [ERROR]로 시작하는 에러 메시지 출력
  - [ ] 구분자가 잘못 입력된 경우 [ERROR]: 구분자 입력이 잘못되었습니다.
  - [ ] 커스텀 구분자로 숫자, "//", "." 혹은 "\n"이 입력된 경우 [ERROR]: 유효하지 않은 커스텀 구분자입니다.
  - [ ] 커스텀 구분자를 입력하지 않은 경우 [ERROR]: 커스텀 구분자가 입력되지 않았습니다.
  - [ ] 이미 delimiters 배열에 들어있는 문자열을 커스텀 문자열로 입력할 경우 [ERROR]: 이미 등록된 구분자입니다.
  - [x] 그 외의 에러 [ERROR]: 예상치 못한 에러가 발생하였습니다.

# 📋 문제 해결과정

## 설계

![image](https://github.com/user-attachments/assets/2b8da393-05a1-4cfc-9a39-83462977fb86)

# 📺 실행 결과

# 📕 TMI

- https://github.com/woowacourse-projects/javascript-mission-utils
- https://gist.github.com/stephenparish/9941e89d80e2bc58a153
- https://hamait.tistory.com/342

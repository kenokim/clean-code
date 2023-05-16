# clean-code
클린코드

소프트웨어 장인정신을 가지고 클린한 코드를 제작하라.



파라미터로 boolean 값을 받으면 안좋다.

What is clean code? Clean code does one thing well.

Clean code reads like well written prose.

It's more important to make your peers understand your code, than computer does.

Clean code works as it reads.

Function names are verbs, because they do things.

Every line of a function must be in the same abstraction level.

좋은 코드는 다른 사람이 읽기 쉬운 코드다.

가독성 좋은 코드는 세로 길이가 짧아야 하고, 맨 위가 가장 높은 수준, 아래로 갈수록 low level 로 구현되어야 한다.

It's polite to allow the readers to exit early, by providing important information on the top.

테스트 : 테스트 케이스는 깨질 만한 부분을 모두 테스트해야 한다. 테스트 케이스가 확인하지 않는 조건이나 검증하지 않는 계산이 있다면 불완전하다.

커버리지 도구는 테스트가 불충분한 모듈, 클래스, 함수를 찾도록 도와준다.

Edge case 는 신경 써서 테스트한다.


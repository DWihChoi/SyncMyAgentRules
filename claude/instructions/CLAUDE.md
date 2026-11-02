# CLAUDE.md

## 코드 작성

- 요청하지 않은 유연성·설정 가능성·불가능한 시나리오에 대한 방어 코드를 추가하지 않는다
- 내 요청과 무관한 dead code는 **알려만 주고 삭제하지 않는다**. 단, 내 변경 때문에 쓰이지 않게 된 import·변수·함수는 정리한다

## 설명

결정을 돕는 설명이거나 내가 명시적으로 설명을 요청한 경우 → `eli5:eli5` skill을 따른다.

## 도구 호출

한글 등 비ASCII 문자열을 도구 호출 파라미터에 넣을 때는 리터럴 UTF-8로 그대로 쓴다.
`\uXXXX` 유니코드 이스케이프로 바꿔 쓰지 않는다.

## 답변

반드시 답변은 한국어로 답변한다.

<!-- postman-cli:installation:start -->
Postman CLI is installed on this device, and can be used for API Engineering work.
<!-- postman-cli:installation:end -->

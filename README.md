# 🌱 Spring 심화 프로젝트 – 리팩토링 & 테스트 실습
본 프로젝트는 이미 구현된 Spring 코드를 기반으로, 리팩토링하고 테스트코드로 검증하는데 초점을 둔 프로젝트입니다.
아래는 프로젝트 진행 내용과 학습한 주제에 대해서 정리한 문서입니다.

# 🪜 진행 단계
## Lv 0. 프로젝트 세팅 - 에러 분석
- 실행 오류 분석
- application.yml 파일 이해

## Lv 1. ArgumentResolver
- ArgumentResolver의 설정 및 동작 이해
- WebMvcConfigurer 이해
- `@Component` 이해

## Lv 2. 코드 개선
### ✔️ 1. Early Return 적용
- 예외 조건을 먼저 반환하는 구조로 개선

### ✔️ 2. 불필요한 if-else 피하기
- 가독성을 해치는 중첩 if 제거

### ✔️ 3. Validation
- 역할 분리를 위해 Validation을 이용하여 유효성 검사하도록 개선

## Lv 3. N+1 문제
- `fetch join` vs `@EntityGraph` 비교

## Lv 4. 테스트코드 연습
- Given-When-Then 패턴
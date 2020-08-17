# rust_for_beginners

## Intro
- [러스트 기본 문서](https://rinthel.github.io/rust-lang-book-ko/) 보면서 알게 된 것들을 기록한다.
- 문서에 나오는 프로젝트 내용 및 코드를 포함한다.
- 기록용이다.

## Commands
`cargo`는 `rust`의 패키지 매니저다.
- `cargo check`: 컴파일 체크 (빠름)
- `cargo build`: 빌드
- `cargo run`: 빌드 후 실행

## 배운 것
- Guessing game
  - `let`, `match`, `extern crate`, `std fn` 등을 알게 됨
  - dependency를 `Cargo.toml`에 추가해서 외부 depedency를 가져 와서 사용할 수 있음
  - 변수 선언은 `let`으로 하는데 mutable한지는 `mut`을 추가로 선언하면서 관리
  - 타입 변형 등을 해서 같은 이름의 변수를 새로 선언해서 `Shadowing`할 수 있음
  - 예외 처리 방식을 `expect`에서 `match` 표현식으로 바꿔서 처리할 수 있음
  - `문자열의 parse 메소드`가 문자열을 숫자로 바꾸는데 `: u32` 처럼 타입을 명시해야 함.
# java-calculator-8

우아한테크코스 프리코스 문자열 계산기 미션을 위한 Java 연습 저장소입니다.

현재 저장소는 미션 초기 세팅 상태에 가깝고, `Application.java`에 구현 TODO가 남아 있습니다. 포트폴리오 프로젝트라기보다는 Java 미션 환경과 Gradle 기반 테스트 구조를 연습하기 위한 저장소로 분류했습니다.

## 기술 스택

- Java 21
- Gradle
- JUnit 5
- Mission Utils

## 프로젝트 구조

```text
src
├── main/java/calculator
│   └── Application.java
└── test/java/calculator
    └── ApplicationTest.java
```

## 실행 방법

```bash
git clone https://github.com/boclair98/java-calculator-8.git
cd java-calculator-8
./gradlew test
```

Windows 환경:

```bash
gradlew.bat test
```

## 구현 예정

- 쉼표와 콜론 기준 문자열 숫자 합산
- 커스텀 구분자 처리
- 음수 입력 예외 처리
- 입력값 검증 테스트 작성

## 포트폴리오 메모

이 저장소는 완성 프로젝트보다 프리코스 미션 준비용 저장소입니다. GitHub 프로필에서는 주요 프로젝트보다 낮은 우선순위로 두는 것이 좋습니다.

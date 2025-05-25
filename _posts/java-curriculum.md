# 자바 백엔드 개발자 학습 커리큘럼

> Nest.js 개발자가 자바 백엔드 개발자로 성장하기 위한 학습 로드맵입니다.

## 목차

1. [자바 기초 문법](#1-자바-기초-문법)
2. [객체지향 프로그래밍](#2-객체지향-프로그래밍)
3. [자바 핵심 기능](#3-자바-핵심-기능)
4. [실무 필수 개념](#4-실무-필수-개념)
5. [테스트](#5-테스트)
6. [실전 프로젝트](#6-실전-프로젝트)
7. [성능 최적화](#7-성능-최적화)
8. [보안](#8-보안)
9. [DevOps](#9-devops)

## 1. 자바 기초 문법

### 1.1 변수와 데이터 타입

- 기본 타입 (int, double, boolean 등)
- 참조 타입 (String, 배열 등)
- 타입 변환 (형변환)
- 상수와 리터럴

### 1.2 연산자

- 산술 연산자 (+, -, \*, /, %)
- 비교 연산자 (>, <, ==, !=)
- 논리 연산자 (&&, ||, !)
- 비트 연산자 (&, |, ^, ~)
- 삼항 연산자 (?:)

### 1.3 제어문

- 조건문 (if-else, switch)
- 반복문 (for, while, do-while)
- break, continue

## 2. 객체지향 프로그래밍

### 2.1 클래스와 객체

- 클래스 정의
- 객체 생성
- 필드와 메서드
- 생성자

### 2.2 접근 제어자

- public, private, protected, default
- getter/setter

### 2.3 상속과 다형성

- extends, implements
- 오버라이딩, 오버로딩
- super, this

### 2.4 추상 클래스와 인터페이스

- abstract class
- interface
- default 메서드

## 3. 자바 핵심 기능

### 3.1 예외 처리

- try-catch-finally
- throws
- 커스텀 예외

### 3.2 컬렉션 프레임워크

- List (ArrayList, LinkedList)
- Set (HashSet, TreeSet)
- Map (HashMap, TreeMap)

### 3.3 제네릭

- 제네릭 클래스
- 제네릭 메서드
- 와일드카드

### 3.4 람다와 스트림

- 함수형 인터페이스
- 람다 표현식
- 스트림 API

## 4. 실무 필수 개념

### 4.1 파일 입출력

- File 클래스
- InputStream/OutputStream
- Reader/Writer

### 4.2 날짜와 시간

- LocalDate, LocalTime
- LocalDateTime
- DateTimeFormatter

### 4.3 정규표현식

- Pattern, Matcher
- 문자열 검색/치환

### 4.4 로깅

- System.out.println vs 로깅
- Log4j, Logback

## 5. 테스트

### 5.1 단위 테스트

- JUnit 5
- 테스트 케이스 작성
- Mockito

### 5.2 테스트 주도 개발(TDD)

- Red-Green-Refactor
- 테스트 커버리지

## 6. 실전 프로젝트

### 6.1 간단한 콘솔 애플리케이션

- 학생 관리 시스템
- 도서 관리 시스템

### 6.2 Spring Boot 기초

- REST API
- 데이터베이스 연동
- 의존성 주입

## 7. 성능 최적화

### 7.1 JVM 이해

- JVM 구조
- 가비지 컬렉션
- 메모리 관리

### 7.2 성능 분석

- JVM 모니터링
- 프로파일링
- 병목 현상 분석

### 7.3 최적화 기법

- 문자열 최적화
- 컬렉션 최적화
- 동시성 처리

## 8. 보안

### 8.1 자바 보안 기초

- 암호화/복호화
- 해시 함수
- 디지털 서명

### 8.2 웹 보안

- XSS 방어
- CSRF 방어
- SQL 인젝션 방어

### 8.3 인증/인가

- JWT
- OAuth2
- Spring Security

## 9. DevOps

### 9.1 컨테이너화

- Docker 기초
- Docker Compose
- 컨테이너 보안

### 9.2 CI/CD

- Jenkins
- GitHub Actions
- 자동화 테스트

### 9.3 모니터링

- Prometheus
- Grafana
- ELK Stack

---

## 학습 방법

### 각 주제별 학습 순서

1. 이론 설명
2. 실습 예제
3. 실무 적용 방법
4. Nest.js와의 비교
5. 성능/보안 고려사항
6. DevOps 적용

### 실습 환경

- JDK 17
- IntelliJ IDEA
- Gradle
- Git
- Docker
- Jenkins/GitHub Actions

### 참고 자료

- [Oracle Java Documentation](https://docs.oracle.com/en/java/)
- [Spring Boot Documentation](https://spring.io/projects/spring-boot)
- [JUnit 5 User Guide](https://junit.org/junit5/docs/current/user-guide/)
- [Java Performance Tuning Guide](https://www.oracle.com/java/technologies/javase/performance.html)
- [OWASP Java Security Guide](https://owasp.org/www-project-java-security-guide/)
- [Docker Documentation](https://docs.docker.com/)
- [Jenkins User Documentation](https://www.jenkins.io/doc/)

### 실무 적용 시 고려사항

1. **코드 품질**

   - 코드 컨벤션
   - 리팩토링
   - 디자인 패턴
   - 코드 리뷰

2. **협업 도구**

   - Git Flow
   - 코드 리뷰
   - CI/CD
   - 이슈 트래킹

3. **문서화**

   - JavaDoc
   - API 문서
   - 아키텍처 문서
   - 운영 매뉴얼

4. **운영 환경**
   - 클라우드 서비스 (AWS/GCP/Azure)
   - 서버리스 아키텍처
   - 마이크로서비스
   - 쿠버네티스

### 학습 로드맵

1. **1단계: 기초 (1-2개월)**

   - 자바 기초 문법
   - 객체지향 프로그래밍
   - Git 기초

2. **2단계: 심화 (2-3개월)**

   - 자바 핵심 기능
   - Spring Boot 기초
   - 데이터베이스

3. **3단계: 실무 (3-4개월)**

   - 실전 프로젝트
   - 성능 최적화
   - 보안

4. **4단계: DevOps (2-3개월)**
   - Docker
   - CI/CD
   - 모니터링

---

> 작성일: 2024년 3월
> 작성자: serve1103
>
> 이 커리큘럼은 지속적으로 업데이트될 예정입니다.

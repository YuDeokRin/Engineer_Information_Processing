# Chapter 03. 애플리케이션 설계

**모듈 개념** 

**모듈 특징** - 독립성 높을수록 , 모듈의 결합도 낮게, 응집도 높게 , 모듈의 크기는 작게   

**공통 모듈 개념 :** 

**공통 모듈 원칙(정명완일추)**

- 정확성
- 명확성
- 완전성
- 일관성
- 추적성

**모듈화 개념**

**모듈화 기법**

| 루틴(Routine) | 소프트웨어에서 특정 동작을 수행하는 일련의 코드로 기능을 가진  |
| --- | --- |
| 메인루틴 |  |
| 서브루틴 |  |

**바람직한 모듈 설계 방안 -중요** 

- 결합도 낮추고 응집도 높인다.
- 모듈의 복잡도와 중복성을 줄이고 일관성을 유지한다.
- 모듈의 기능은 예측이 가능해야 하며, 지나치게 제한적이어서는 안 된다.
- 적당한 모듈의 크기를 유지한다. (Mccabe)
- 모듈 간의 효과적인
- 유지 보수가 용이해야 하고 이식성을 고려해야 한다.

**모듈 개수 및 비용 간 상관관계** 

**모듈화 유형** 

| 응집도 |  |
| --- | --- |
| 결합도 |  |

**팬인/팬아웃**

F : 팬인 2개들어오는것   팬 아웃 1개 나가는것  

---

**공통 모듈 설계** 

**설계 모델링 개념** 

**설계 모델링 원칙**

- 구조화
- 하나의 함수 안에
- 모듈 단위
- 계층적 구조

**설계 모듈링 유형**

- 구조모델링
- 

**소프트웨어 설계 유형 - 중요** 

- 자료구조 설계
- 아키텍쳐 설계
- 인터페이스 설계

**소프트웨어 설계 유형 - 중요** 

- 프로지서 설계
- 협약에 의한 설계   -중요

**협약에 의한 설계** - 중요

- 선행 조건
- 결과 조건
- 불변 조건

**소프트웨어 설계 원리 -중요**

- 하향식(모듈)
- 상향식(자아인프)
- 상위, 하위

| 상향식 설계 |  |
| --- | --- |
| 하향식 설계 |  |

코드 설계 개념 

**코드의 기능**

| 표준화 |  |
| --- | --- |
| 분류 |  |
| 식별 |  |
| 배열 |  |
| 간소화 |  |
| 연상 |  |
| 암호화 |  |
| 오류검출 |  |

**코드 설계 종류**

| 연상 코드 |  |
| --- | --- |
| 블록 코드 |  |
| 순차 코드 |  |
| 표의 숫자 코드 |  |
| 십진 코드 |  |
| 그룹 분류식 코드 |  |

**코드 오류 종류** 

| 사본 오류(Transcrip) |  |
| --- | --- |
| 전위 오류 |  |
| 생략 오류(Omission Error) |  |
| 첨가 오류 (Addition Error) |  |
| 이중 전위 오류 |  |

**HIPO 개념**

시스템의 분석 및 설계나 문서화할 때 사용되며, 하향식 소프트웨어 개발을 위한 문서화 도구

**HIPO 특징**

- 체계적인 문서 관리가 가능하다.
- 기호, 도표 등을 사용해서 보기가 쉽고 이해도 쉽다
- 기능과 자료의 의존관계를 동시에 표현할 수 있다.
- 변경, 유지보수가 용이하다.
- HIPO 차트

HIPO 차트 종류

| 가시적 도표 |  |
| --- | --- |
| 총체적 도표 |  |
| 세부적 도표 |  |

---

**소프트웨어 아키텍쳐 개념**

**소프트웨어 아키텍처 프레임워크 개념**

**소프트웨어 아키텍처 4+1 뷰 개념**

**소프트웨어 아키텍처 4+1 뷰 구성요소 (유논프구배)**

- 유스케이스 뷰
- 논리 뷰
- 프로세스 뷰
- 구현 뷰
- 배포 뷰 (=배치 뷰)

**소프트웨어 아키텍처 비용 평가 모델 개념**

**아키텍처 비용 평가 모델 종류 (SACAA)**

- SAAM : 변경 용이성과 기능성에 집중, 평가가 용이하여 경험이 없는 조직에서도 활용 가능
- ATAM :
- CBAM : 경제적 의사결정에 대한 요구를 충조
- ADR
- ARID

**소프트웨어 아키텍처 패턴 개념**

소프트웨어를 설계할 때 참조할 수 있는 전형적인 해결 방식

**소프트웨어 아키텍처 패턴 유형**

- 계층화 패턴
- 클라이언트 - 서버 패턴
- 파이프 - 필터 패턴
- 브로커 패턴
- MVC 패턴
- 마스터-슬레이브 패턴 예) 실기간 시스템

**소프트웨어 아키텍처 품질 속성**

| 시스템 품질 속성(가변성 보사시 ) | 가용성, 변경 용이성, 성능, 보안성, 사용 편의성, 시험 용이성 |
| --- | --- |
| 비지니스 품질 속성 |  |
| 아키텍처 품질 속성 |  |

---

**객체 지향 개념**

실세계의 개체를 속성과 메서드가 결합한 형태의 객체로 표현하는 기법

**객체지향 구성요소(클객메메인속)**

- 클래스
- 객체
- 메소드
- 메시지
- 인스턴스
- 속성

**객체지향 기법(캡상다 추정관)**

- 캡슐화
- 상속성
- 다형성
- 추상화
- 정보은닉
- 관계성

**관계성(집분연일특)**

| 연관화 관계 | is-member-of관계 |
| --- | --- |
| 집단화 관계 |  |
| 분류화 관계 |  |
| 일반화 관계 |  |
| 특수화 관계 |  |

**객체지향 설계 원칙(SOLID) - 중요**

- 단일 책임의 원칙(single)
- 개방폐쇄의 원칙(open)
- 리스코프 치환의 원칙(Liskov)
- 인터페이스 분리의 원칙(Interface)
- 의존성 역전의 원칙(Dependency) ****

객체지향 방법론 종류 

| OOSE(야콥슨) |  |
| --- | --- |
| OMT(럼바우) | 객동기 -객체모델링(Object Modeling) , 동적모델링, 기능 모델링 |
| OOD(부치) |  |

COad와 Yourdon 방법

Wirfs-Brocks 방법

객 : 객체 다이어그램

동 : 상태다이어그램 

기 : 자료흐름도

---

**디자인 패턴** 

디자인 패턴 개념

디자인 패턴 구성 요소(패문솔 사결샘)

- 패턴명
- 문제 및 배경
- 솔루션
- 사례
- 결과
- 샘플코드

디자인패턴에 목적(생구행)

생구행

 

**생성 패턴(생빌프로팩앱싱)** 

- 생성 패턴
- 빌더 패턴
- 프로토 타입
- 팩토리 메소드
- 앱스트랙 팩토리(추상 팩토리)
- 싱글톤

**구조 패턴** (구브데 퍼플 프록 컴어)

- 구조
- 브리지
- 데코레이터
- 퍼사이드
- 플라이 웨이트
- 프록시
- 컴포지트
- 어뎁터

**디자인패턴의 장단점** 

| 장점 | 단점 |
| --- | --- |
| 요구사항 변경에 따른 소스 코드 변경을 최소화할 수 있게 해줌 |  |
| 재사용 통함 개발 시간 단축 가능 |  |
| 소프트웨어 구조 파악 용이 |  |
| 생산성 |  |

---

**내 -외부 인터페이스 요구사항의 개념**

**내-외부 인터페이스 요구사항의 구성**

- 인터페이스 이름
- 연계대상 시스템
- 연계범위 및 내용
- 연계 방식
- 송신데이터
- 인터페이스 주기

내-외부 인터페이스 요구사항의 분류 

**요구공학 개념 (도분명확)**

- 도출
- 분석
- 명세
- 확인 및 검증

**요구공학의 개념**

**요구사항의 분류** 

- 기능적 요구사항(기완일)
    - 기능성
    - 완전성
    - 일관성
- 비기능적 요구사항
    - 신뢰성
    - 사용성
    - 효율성
    - 유지보수성
    - 의식성

---

## 인터페이스 요구사항 확인(2)

- 도출
- 분석
- 명세
- 확인 및 검증
    
    

**요구사항 명세 원리 및 검증 항목(명완검 일수추개)**

- 명확성
- 완전성
- 검증 가능성
- 일관성
- 수정 용이성
- 추적 가능성
- 개발 후 이용성

요구사항 관리단계(협기변확)

- 

요구사항 도출 단계 주요기법, 산출물 

- 인터뷰 - 직접 대화
- 브레인스토밍 - 자유롭게 회의
- 델파이 - 전문가
- 롤플레잉 - 사용자 역할
- 워크숍 - 전문적 지식 공유
- 설문지 - 다수

요구사항 명세 단계 주요 기법, 산출물

- 정형명세기법
- 비정형명세기법
- 요구사항 명세서

**요구사항 확인 및 검증 단계** 

- 요구사항 검토
- 정형기술 검토활용
- 프로토타이핑 활용
- 모델검증
- 테스트케이스 및 인수 테스트
- CASE 도구
- 베이스라인 설정
- 요구사항 추적표

**요구사항 검토방법**

| 동료검토 |  |
| --- | --- |
| 워크스루 |  |
| 인스펙션 |  |

중요 - 

---

**인터페이스 대상 식별**

**시스템 개념 :**

**시스템 구성요소** 

| 입력 |  |
| --- | --- |
| 출력 |  |
| 처리 |  |
| 제어 |  |
| 피드백 |  |

**시스템 아키텍쳐 개념**

시스템 아키텍쳐는 시스템의 구조, 행위, 동작 원리를 설명하는 프레임워크(틀)

**시스템 아키텍쳐의 기본 요구사항**

- 시스템 구성 및 동작 원리를 나타내고 있어야 함
- 시스템 구성요소에 대해 설계 및 구현을 지원하는 수준으로 자세히 기술
- 구성 요소 간의 관계 및 시스템 외부 환경과의 관계 파악

**시스템 아키텍처 설계 시 중점 고려사항**

시스템 아키텍처 설계 원칙(대확 고운보) 

- 대규모 트랜젝션 처리 및 온라인 성능 보장
- 시스템 아키텍처의 확장성 보장
- 서비스 고가용성 보장
- 운영관리 효율성 강화
- 시스템 보안 강화

**시스템 아키텍처 물리설계**

- 1iter

- 2tier

- 3tier

**인터페이스 시스템 개념**

**인터페이스 시스템 구성**

- 송신시스템
- 수신시스템
- 중계 서버

**인터페이스 시스템 분류 체계**

**인터페이스 시스템 식별 정보**

**인터페이스 시스템의 데이터 표준**

| 인터페이스 데이터 공통부 |  |
| --- | --- |
| 인터페이스 데이터 개별부 |  |
| 인터페이스 데이터 종료부 |  |

**송-수신 전문 구성 사례** 

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

**인터페이스 시스템 처리 프로세스**

---

**내-외부 송 - 수신 연계 방식**

| 직접 연계 방식 |  |
| --- | --- |
| 간접 연계 방식 |  |

**내-외부 송-수신 연계 기술 - 중요** 

- DB링크
- DB connection
- API/openAPI
- JDBC
- 하이퍼링크
- 소켓

**내-외부 송-수신 통신 유형**

| 실시간 | 단방향 |
| --- | --- |
|  | 양방향 |
|  | 동기방식 |
|  | 비동기방식 |
|  | 지연 |
| 배치 | DB/file |

---

인터페이스 오류 유형

| 연계서버 |  |
| --- | --- |
| 송신 시스템 연계 프로그램 |  |
| 연계 데이터 |  |
| 수신 시스템 연계 프로그램 |  |

**인터페이스 설계**

인터페이스 설계는 인터페이스 목록 도출 및 인터페이스 정의서 작성을 통해서 구현된다

**인터페이스 목록 도출**

인터페이스ID, 인터페이스명, 송신시스템, 수신 시스템 , 대내외 구분, 연계방식, 통신 유형, 처리 유형, 주기, 데이터 형식, 관련 요구사항ID 

**인터페이스 정의서 주요 항목(인최크시데)**

- 인터페이스 ID
- 최대 처리 횟수
- 데이터 크기
- 시스템 정보
- 데이터 정보

**인터페이스 설계 프로세스**

1. 양식 준비
2. 인터페이스 기본 정보 작성
3. 송수신 시스템의 정보 작성
4. 프로그램 명세서 확인 및 보완
5. 송수신 데이터 항목 작성
6. 코드 매핑 정보 작성
7. 인터페이스 설계 내용 검토 및 보완

**미들웨어 솔루션 개념 - 중요** 

- 미들웨어 솔류션은 컴퓨터와 컴퓨터 간의 연결을 쉽고 안전하게 할 수 있도록 해주고 이에 대한 관리를 도와주는 소프트웨어
- 클라이언트와 서버간의 통신을 담당하는 시스템 소프트웨어

미들웨어 솔루션 유형(디원메트 레객와)

- DB미들웨어
- 원격 프로시저 호출 RPC
- 메시지 지향 미들웨어
- 트랜잭션 처리 모니터 TP Monitor
- 레거시 웨어 = 기존의 시스템
- 객체기반 미들웨어
- WAS

**EAI개념** 

- 

**ESB개념**

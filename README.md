![header](https://capsule-render.vercel.app/api?type=waving&color=1E90FF&height=220&section=header&text=Kang%20Myoung%20Suk&fontSize=42&animation=fadeIn&fontAlignY=38&desc=Systems%20%26%20Industrial%20Control%20Software%20Engineer&descAlignY=58&fontColor=FFFFFF)

# 강명석 | Systems & Industrial Control Software Engineer

Linux/C/C++ 기반의 실시간·고신뢰 시스템과  
EtherCAT 기반 산업제어 소프트웨어를 개발합니다.

증권 트레이딩 시스템에서 서버 데몬, IPC, TCP/UDP 전문 통신,
DB·공유메모리 연동, 운영 장애 분석과 개선을 경험했습니다.

현재는 산업제어 환경에서 Embedded Linux, EtherCAT, C/C++,
C#/.NET을 연결하며 제어·통신·테스트·모니터링 소프트웨어를
개발하고 있습니다.

> 안 되는 이유보다 되는 방법을 먼저 찾되,  
> 운영 환경에서는 근거, 영향 범위, 복구 경로까지 확인합니다.

<br>

## Current Focus

- EtherCAT 기반 I/O 및 모션 제어
- Embedded Linux와 MCU Firmware 간 통신 및 IPC
- C/C++ 저수준 제어와 C#/.NET GUI·진단 도구 연계
- Serial, Network, Process Data 흐름 분석
- 로그와 상태 데이터를 기반으로 한 장애 재현 및 원인 분석
- 안정성, 유지보수성, Safe State를 고려한 운영 소프트웨어

<br>

## Core Experience

### Real-time & System Software

- Linux 환경의 C/C++ 서버 데몬 개발 및 운영
- IPC, TCP/UDP, 고정 길이 전문, Shared Memory 기반 데이터 처리
- Pro*C 및 SQL 기반 DB 연동
- 프로세스 간 의존성, 기동 순서, 상태 동기화 관리

### Production Troubleshooting

- 로그, DB, Shared Memory 데이터를 대조한 장애 원인 분석
- Core Dump와 gdb Backtrace 기반 크래시 분석
- 운영 코드의 영향 범위를 고려한 최소 변경
- 재현 절차, 예외 조건, 복구 방법을 포함한 문제 해결

### End-to-End Development

- 서버 TR 및 Backend Service 개발
- Delphi/VCL과 Pascal Script 기반 클라이언트 화면 개발
- 서버 요청, 응답 처리, 실시간 데이터 갱신까지 전체 흐름 경험
- C/C++ 제어 계층과 C#/.NET 테스트·모니터링 계층 연계

<br>

## Tech Stack

| Category | Technologies |
|---|---|
| Core Systems | C, C++, Linux, Shell Script, GDB |
| Communication | IPC, TCP/UDP, Shared Memory, Serial |
| Industrial Control | EtherCAT, Embedded Linux, I/O, Motion Control |
| Current Integration | C#, .NET, WPF, gRPC, RPMsg |
| Database | Pro*C, SQL, Goldilocks, Altibase, MySQL |
| Client Application | Delphi, VCL, Pascal Script |
| Previous Projects | Java, Spring Boot, MyBatis, JSP, Kotlin, Android, Firebase |
| Tools | Git, GitHub, VS Code, Visual Studio, IAR |

<br>

## Experience

### 커미조아 | 산업제어 소프트웨어 엔지니어

`2026.06 - Present`

- EtherCAT 기반 산업제어 소프트웨어 및 기술지원 도구 개발
- Embedded Linux와 Firmware·I/O 계층 간 연동 구조 분석
- C/C++ 기반 제어·통신 소프트웨어 개발
- C#/.NET 기반 테스트·모니터링 도구 개발
- 장비 상태, 통신 흐름, 장애 지점을 고려한 진단 및 운영 개선

> 고객사 및 내부 프로젝트의 비공개 정보는 기재하지 않습니다.

### 호아소프트 | 트레이딩 시스템 개발

`2024.02 - 2026.03`

- 국내 증권사 S&T 통합운용 시스템 개발
- 대체거래소 신규 거래 채널 대응
- 증권 트레이딩 시스템 유지보수 및 운영 이슈 대응
- Linux C/C++·Pro*C 기반 서버 데몬 및 TR 서비스 개발
- Delphi/VCL·Pascal Script 기반 트레이딩 화면 개발
- 약 40개의 장전 배치 데몬 운영 및 프로세스 의존성 관리
- 신규 화면 약 20종 개발, 기존 화면 50종 이상 수정
- Core Dump, 로그, DB, Shared Memory 기반 장애 분석

<br>

## Selected Public Projects

### [DadokDadok](https://github.com/myoungsuk/DadokDadok)

Spring, JSP, MyBatis, MySQL 기반의 도서 정보 및 독서 커뮤니티 서비스

- 5인 팀 팀장으로 역할 분담, 일정 관리, 회의 진행
- 35,000건 이상의 도서 데이터 처리
- ISBN 기준 중복 제거 및 기존 데이터 일괄 조회
- MyBatis Bulk Insert와 Batch 기반 저장 성능 개선
- 멀티캠퍼스 최종 프로젝트 우수상

### [Mobile Employee ID](https://github.com/Mobile-Employee-ID)

Kotlin, Android, Bluetooth, Firebase 기반 모바일 사원증

- Android 화면 및 기능 구현
- Bluetooth 서버 연동
- 충북대학교 캡스톤디자인 우수상

### [Chungbot](https://github.com/myoungsuk/Chungbot-master)

Dialogflow와 Firebase를 연동한 Android 챗봇 애플리케이션

- 외부 AI API 연동
- 사용자 질의와 응답 처리
- Firebase 기반 데이터 관리

<br>

## Engineering Style

- 기능 하나보다 시스템 전체의 데이터 흐름을 먼저 확인합니다.
- 결과만 보지 않고 입력값, 상태, 예외 조건과 내부 로직을 함께 검증합니다.
- 장애 발생 시 추측보다 로그와 재현 가능한 증거를 우선합니다.
- 운영 중인 시스템에서는 영향 범위와 롤백 가능성을 고려합니다.
- 새로운 도메인에서도 기존 구조와 책임 경계를 먼저 파악합니다.

<br>

## Education & Awards

- 충북대학교 소프트웨어공학과 졸업
- 멀티캠퍼스 백엔드 부트캠프 18기 수료
- 멀티캠퍼스 최종 프로젝트 우수상
- 충북대학교 캡스톤디자인 졸업작품전 우수상

<br>

## Contact

- Email: [k4858678@gmail.com](mailto:k4858678@gmail.com)
- Blog: [mangseok.tistory.com](https://mangseok.tistory.com/)

![footer](https://capsule-render.vercel.app/api?type=waving&color=1E90FF&height=100&section=footer)

# 산업제어 소프트웨어 엔지니어

커미조아에서 EtherCAT 기반 I/O·모션 제어 소프트웨어를 만들고 있습니다.
그 전 2년 동안은 증권사 트레이딩 시스템의 Linux C/C++ 서버와 화면을 개발하고 운영했습니다.

[기술 블로그](https://mangseok.tistory.com/) · [메일](mailto:k4858678@gmail.com) · [Instagram](https://www.instagram.com/myoung_suk.212/)

## 경력

### 커미조아 · 산업제어 소프트웨어 엔지니어 (2026.06 ~ )

#### 장비용 HMI 프로젝트

- 반도체 장비용 7인치 HMI 화면 개발
- 패널 전용 IDE(Comfile Studio) 기반 화면·스크립트 개발
- Qt/QML 기반 HMI 개발
- 장비와 RS-485 Modbus RTU 통신

#### 장비 I/O 제어 보드 프로젝트

- TI J722S(AM67) 기반 장비 I/O 제어 보드 개발
- Linux I/O 데몬, R5F·STM32 펌웨어
- 보드 유지보수 REST API, Yocto 빌드·배포
- 신규 보드 부팅·DDR·Ethernet 문제 진단 (JTAG·UART)

#### 웹사이트 통합 AI 챗봇 프로젝트

- 회사 웹사이트용 다용도 AI 챗봇 개발 (제품·기술지원, 구매·영업 문의)
- ASP.NET Core Blazor, PostgreSQL, Docker Compose
- OpenAI Responses API·Vector Store 기반 문서 검색
- 고객 공개 문서만 검색하도록 설계 (내부 자료 분리)

#### 기술지원

- EtherCAT·모션 제품(SW EtherCAT Master, ComiIDE, EtherCAT Slave 등) 고객 기술지원
- 고객 장애 원인 분석: 패킷 캡처, Windows 이벤트 로그, 장비 로그로 재현
- 매뉴얼·FAQ·지원 기록·사내 소스를 한 번에 찾는 기술지원 문서 검색 도구 구축 (Python)
- 신입 엔지니어 8주 교육 과정 설계

### 호아소프트 · 트레이딩 시스템 개발 (2024.02 ~ 2026.03)

- 국내 증권사 S&T 통합운용 시스템 개발, 대체거래소 신규 거래 채널 대응
- Linux C/C++·Pro*C 서버 데몬과 TR 서비스 개발 (IPC, TCP/UDP, 고정 길이 전문, Shared Memory)
- Delphi/VCL·Pascal Script 트레이딩 화면 개발
- 운영 장애 분석: Core Dump와 GDB backtrace, 로그·DB·Shared Memory 대조, 재현한 뒤 방어 로직 보완

## 기술

| 분야 | 기술 |
|---|---|
| 언어·환경 | C, C++, Linux, Yocto, Shell Script, GDB |
| 통신 | EtherCAT, Modbus RTU(RS-485), IPC, TCP/UDP, Shared Memory, Serial, RPMsg, gRPC |
| 응용 | C#, .NET, WPF, ASP.NET Core Blazor, Qt/QML, Delphi/VCL, Pascal Script, OpenAI API |
| DB | Pro*C, SQL, Goldilocks, Altibase, PostgreSQL, MySQL |
| 도구 | Git, Visual Studio, VS Code, IAR, TI CCS, Docker |
| 예전 프로젝트 | Java, Spring Boot, MyBatis, JSP, Kotlin, Android, Firebase |

## 공개 프로젝트

학교와 부트캠프에서 한 프로젝트입니다.

### [DadokDadok](https://github.com/myoungsuk/DadokDadok)

도서 정보·독서 커뮤니티 웹 서비스 (Spring, JSP, MyBatis, MySQL)

- 5인 팀 팀장
- 도서 데이터 35,000건 이상 ISBN 기준 중복 제거
- MyBatis bulk insert·batch로 저장 속도 개선
- 멀티캠퍼스 최종 프로젝트 우수상

### [Mobile Employee ID](https://github.com/Mobile-Employee-ID)

모바일 사원증 Android 앱 (Kotlin, Bluetooth, Firebase)

- Android 화면과 주요 기능 구현
- Bluetooth 서버 연동
- 충북대학교 캡스톤디자인 우수상

### [Chungbot](https://github.com/myoungsuk/Chungbot-master)

충북대 챗봇 Android 앱 (Dialogflow, Firebase)

## 학력

- 충북대학교 소프트웨어공학과 졸업
- 멀티캠퍼스 백엔드 부트캠프 18기 수료

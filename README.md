# 안녕하세요, 백엔드 개발자를 준비하는 we5046입니다 👋

Java·Spring으로 웹 백엔드를 만들고, C++ IOCP로 게임 서버를 공부합니다.
동작하는 데서 멈추지 않고, 사용자가 늘었을 때 어디가 먼저 문제가 되는지 재현하고 고치는 데 관심이 있습니다.

## 지금 하는 것

- 팀 프로젝트 **TeenyMoney**를 AWS에서 Oracle Cloud(OCI)로 이전해 운영하고 있습니다.
- Spring Legacy + MyBatis로 만든 게시판을 **Spring Boot 3 + JPA**로 다시 만들고 있습니다.

## 기술

**웹 백엔드**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)

**인프라**

![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**게임 서버 · 클라이언트**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Windows IOCP](https://img.shields.io/badge/Windows_IOCP-0078D6?style=flat-square)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square)
![Unity](https://img.shields.io/badge/Unity-222222?style=flat-square&logo=unity&logoColor=white)

## 대표 프로젝트

### TeenyMoney — 부모와 자녀가 함께 만드는 작은 금융사회 전자지갑

KB IT's Your Life 7기 팀 프로젝트 · 팀장 · [서비스 바로가기](https://www.teenymoney2.kro.kr)

![TeenyMoney 프로젝트 한 장 요약](assets/teenymoney-summary.png)

- **공통 기반**: Spring MVC 프로젝트 구조, 공통 API 응답과 예외 처리, MyBatis·MySQL 연동
- **인증**: Spring Security + JWT, Redis에 Refresh Token을 저장해 토큰 재발급과 로그아웃 구현
- **회원·가족 연동**: 회원가입·로그인, 법정대리인 동의, S3 프로필 이미지 업로드, 부모와 자녀 연동
- **퀘스트**: 부모가 퀘스트를 만들고, 자녀가 수행에 성공하면 용돈과 티니점수를 받는 기능
- **머니리포트**: 이번 달 소비 패턴을 한눈에 보여 주는 기능
- **인프라**: AWS EC2에 Nginx와 Tomcat 연결, MySQL·Redis는 Docker 컨테이너로 운영, HTTPS 적용
- **협업 환경**: GitHub Issue·PR 템플릿, GitHub Actions 기반 CI
- **이전**: AWS 이용 기간이 끝난 뒤 서비스를 Oracle Cloud(OCI)로 이전

### 그 밖의 프로젝트

| 프로젝트 | 설명 | 기술 |
| --- | --- | --- |
| [IOCP-GameChatServer](https://github.com/we5046/IOCP-GameChatServer) | 비동기 멀티플레이 채팅 서버. 네트워크 I/O는 워커 스레드에서 병렬로, 게임 로직은 단일 스레드에서 직렬로 처리해 Player·Room에 락이 필요 없는 구조. 실시간 2인 대전 서버로 확장 중 | C++17, Winsock2, IOCP |
| [BombArenaClient](https://github.com/we5046/BombArenaClient) | 위 서버와 짝을 이루는 2D 폭탄 대전 클라이언트. 판정은 서버가 하고 클라이언트는 입력 전송과 화면 표시만 담당 | Unity 6, C# |
| [Fullstack_Proejct_A](https://github.com/we5046/Fullstack_Proejct_A) | 게시판·인증·갤러리를 REST API와 화면으로 나누어 구현한 풀스택 학습 프로젝트 | Spring MVC, Spring Security, MyBatis, Vue 3 |

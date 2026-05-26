<h1 align="left">김경민</h1>

<p align="left">
  <strong>백엔드 개발자 · 4년차</strong><br />
  Java/Spring 기반 API 설계, 비동기 처리, 실시간 메시징, 운영 인프라를 다룹니다.
</p>

<p align="left">
  공공기관·엔터프라이즈 시스템에서 API·DB 설계, 외부 API 비동기 처리,
  STOMP/WebSocket 기반 실시간 기능, Jenkins/Nginx 기반 배포 환경 구성을 맡아왔습니다.
</p>

<p align="left">
  <a href="mailto:gang.dev0nly@gmail.com"><img src="https://img.shields.io/badge/Email-gang.dev0nly%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://work-history.gang-dev0nly.co.kr/"><img src="https://img.shields.io/badge/Resume-work--history-111827?style=flat-square&logo=readthedocs&logoColor=white" alt="Resume" /></a>
  <a href="https://www.linkedin.com/in/%EA%B2%BD%EB%AF%BC-%EA%B9%80-841a69340/"><img src="https://img.shields.io/badge/LinkedIn-Kyeongmin%20Kim-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<br />

## 요약

- Java/Spring 기반 백엔드 개발을 중심으로, 프로젝트 성격에 따라 단일 모듈과 멀티모듈 구조를 선택해 적용했습니다.
- WebFlux/WebClient, Kafka, Redis Pub/Sub, STOMP/WebSocket, SSE 기반의 비동기 처리와 실시간 상태 전달 기능을 개발했습니다.
- MyBatis, JPA, jOOQ를 사용해 CRUD 생산성과 복잡 쿼리 제어가 모두 필요한 데이터 접근 계층을 구현했습니다.
- Nginx, Apache, Tomcat, JBoss, Jeus/WebToB, Jenkins, GitLab Runner, Docker 기반 운영·배포 환경을 구성했습니다.
- **SCOA Workmate**에서 Java 21, Spring Boot 3.4, WebFlux, R2DBC, Kafka, PostgreSQL, Redis 기반 문서 처리 파이프라인을 개발하고 있습니다. Kafka message key와 requestId 기준으로 요청 이력, 처리 로그, 결과 이벤트를 연결하고, 중복 이벤트 수신을 고려해 상태 갱신 흐름을 정리했습니다.
- **TTA AI 신뢰성 검·인증 도구**에서 외부 LLM API 일괄 호출 흐름을 WebFlux/WebClient 기반으로 정리해 다건 요청 응답 시간을 12,514ms에서 1,890ms로 줄였습니다.
- **미래엔 엠티처 교수활동 플랫폼 리뉴얼**에서 상세 페이지 조회 로직의 반복 I/O와 중복 데이터 조립 문제를 줄이고, MyBatis resultMap/collection 매핑으로 응답 시간을 4,062ms에서 135ms로 개선했습니다.
- **자사 STOMP 채팅 서버 / 키오스크 앱**에서 Redis Pub/Sub, STOMP/WebSocket 기반 실시간 주문·채팅 흐름을 구현하고, 동일 부하 시나리오 기준 오류율을 20.54%에서 11.71%로 낮췄습니다.
- TTA 온라인평가시스템, 국립과천과학관 전시물품관리시스템, 보건복지부 금연길라잡이 리뉴얼에서 API 개발, 레거시 분석, 외부 연계 유지보수, 배포 파이프라인 구성을 담당했습니다.

<br />

## 기술

- **Backend**: Java, Spring Boot, WebFlux, WebClient, MyBatis, JPA, jOOQ, STOMP
- **Data**: PostgreSQL, MySQL, MariaDB, Oracle, MongoDB, Redis
- **Messaging / Realtime**: Kafka, Redis Pub/Sub, WebSocket, SSE
- **Infra / DevOps**: Nginx, Apache, Tomcat, JBoss, Jeus/WebToB, Jenkins, GitLab Runner, Docker, AWS EC2/S3, MinIO, Firebase FCM
- **Frontend / App**: JSP, Thymeleaf, JavaScript, HTML/CSS, Flutter, Dart

<br />

## 일하는 방식

- 성능 개선은 감이 아니라 동일 시나리오의 before/after 수치로 확인합니다.
- 기술은 사용 경험을 늘리기 위해 고르기보다, 현재 문제와 운영 제약에 맞는지 기준을 세워 선택합니다.
- AI 개발 도구는 반복 구현, 리팩토링, 문서화 보조에 활용하되 요구사항 해석, 아키텍처 판단, 코드 검증은 직접 책임집니다.

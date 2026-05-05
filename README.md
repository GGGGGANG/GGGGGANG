<h1 align="left">김경민</h1>

<p align="left">
  <strong>백엔드 개발자 · 4년차</strong><br />
  Java, Spring Boot, WebFlux, Kafka, Redis, PostgreSQL, 운영 인프라
</p>

<p align="left">
  공공기관·엔터프라이즈 시스템에서 API 설계, 데이터 처리, 비동기 파이프라인, 실시간 메시징, 배포·운영 환경 구성을 맡아왔습니다.
</p>

<p align="left">
  <a href="mailto:gang.dev0nly@gmail.com"><img src="https://img.shields.io/badge/Email-gang.dev0nly%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/GGGGGANG"><img src="https://img.shields.io/badge/GitHub-GGGGGANG-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://imported-fragrance-c9e.notion.site/study-3352ed06337f80f49528d006cf7d6326?source=copy_link"><img src="https://img.shields.io/badge/Study%20Blog-Notion-000000?style=flat-square&logo=notion&logoColor=white" alt="Study Blog" /></a>
  <a href="https://www.linkedin.com/in/%EA%B2%BD%EB%AF%BC-%EA%B9%80-841a69340/"><img src="https://img.shields.io/badge/LinkedIn-Kyeongmin%20Kim-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<br />

## 소개

- Java/Spring 기반 백엔드 개발을 중심으로, 필요에 따라 JSP, Thymeleaf, Flutter 영역까지 함께 다뤄왔습니다.
- Spring Boot, WebFlux/WebClient, MyBatis, JPA, jOOQ를 사용해 REST API와 데이터 접근 계층을 구현했습니다.
- Kafka, Redis, STOMP/WebSocket, SSE 기반의 비동기 처리와 실시간 상태 전달 기능을 개발했습니다.
- Nginx, Apache, Tomcat, JBoss, Jeus/WebToB, Jenkins, GitLab Runner 등 운영·배포 환경을 직접 구성한 경험이 있습니다.
- 2026년 3월부터 세이코어 개발1팀 부팀장으로 업무 배분, 인력 관리, 프로젝트별 기술스택 결정에 참여하고 있습니다.

<br />

## 주요 경험

### 세이코어 · 백엔드 개발자 / 데브옵스

- **SCOA Workmate**: Java 21, Spring Boot 3.4, WebFlux, R2DBC, Kafka, PostgreSQL, Redis 기반 문서 처리 파이프라인을 개발하고 있습니다. Kafka message key와 requestId 기준으로 요청 이력, 처리 로그, 결과 이벤트를 연결하고, 중복 이벤트 수신을 고려해 상태 갱신 흐름을 정리했습니다. SSE 기반 적재 진행률 스트리밍 API와 Kafka 콜백 전용 Streamer 애플리케이션도 구현했습니다.
- **대용량 파일 업로드 안정화**: init / chunks / complete 3단계 File Chunk Upload 구조를 적용했습니다. Redis TTL로 업로드 세션을 관리하고, MinIO multipart upload와 lifecycle rule을 함께 사용해 실패 후 재시도와 스토리지 정리 기준을 분리했습니다.
- **한국정보통신기술협회(TTA) 온라인평가시스템**: 평가서식, 게시판, 입찰공고, 평가위원 추첨·배치 처리, 파일 첨부, 계정 관리 API를 개발했습니다.
- **국립과천과학관 전시물품관리시스템 / 통합홈페이지**: 전시물품 등록·관리·이력 추적 API를 개발하고, JPA + jOOQ 기반 데이터 접근 계층과 운영 서버 배포 파이프라인을 구성했습니다.
- **보건복지부 금연길라잡이 웹 리뉴얼**: JSP 기반 레거시 구조를 분석해 누락 기능을 보완하고, 상담 시스템, 검색, 소셜 로그인, FCM/SMS, PASS 본인인증 등 외부 연계 기능을 유지보수했습니다.
- **TTA 검·인증 도구**: 외부 API 일괄 호출 흐름을 WebFlux/WebClient 기반으로 정리해 다건 요청 응답 시간을 12,514ms에서 1,890ms로 줄였습니다.

<br />

### 화려한덕후들 · 풀스택 개발자

- **미래엔 엠티처 교수활동 플랫폼 리뉴얼**: 상세 페이지 조회 로직의 반복 I/O와 중복 데이터 조립 문제를 줄이고, 응답 구조에 맞는 MyBatis resultMap/collection 매핑을 적용했습니다. 측정 기준 응답 시간은 4,062ms에서 135ms로 개선했습니다.
- **티맥스소프트 웹사이트 리뉴얼**: 관리자 시스템 API 설계·구현·연동을 담당하고, 컴포넌트별 응답 구조와 CORS·토큰 인증 연동을 처리했습니다.
- **자사 STOMP 채팅 서버 / 키오스크 앱**: Redis Pub/Sub, STOMP/WebSocket 기반 실시간 주문·채팅 흐름을 구현했습니다. 동일 부하 시나리오에서 서버 이중화 구성 후 오류율을 20.54%에서 11.71%로 낮췄습니다.
- **몽고식품 웹사이트 리뉴얼**: 화면 구조, 관리자 기능 API, 비즈니스 로직 구현을 함께 담당했습니다.

<br />

## 기술

- **Backend**: Java, Spring Boot, WebFlux, WebClient, MyBatis, JPA, jOOQ, STOMP
- **Data**: PostgreSQL, MySQL, MariaDB, Oracle, MongoDB, Redis
- **Messaging / Realtime**: Kafka, Redis Pub/Sub, WebSocket, SSE
- **Infra / DevOps**: Nginx, Apache, Tomcat, JBoss, Jeus/WebToB, Jenkins, GitLab Runner, Docker, AWS EC2/S3, MinIO, Firebase FCM
- **Frontend / App**: JSP, Thymeleaf, JavaScript, HTML/CSS, Flutter, Dart

<br />

## 링크

- Study Blog: https://imported-fragrance-c9e.notion.site/study-3352ed06337f80f49528d006cf7d6326?source=copy_link
- LinkedIn: https://www.linkedin.com/in/%EA%B2%BD%EB%AF%BC-%EA%B9%80-841a69340/
- Email: gang.dev0nly@gmail.com

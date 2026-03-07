# 안녕하세요 이근표입니다. 

문제를 직접 찾아 해결하는 과정을 즐깁니다. 단순히 주어진 요구사항을 구현하는 것을 넘어, **진짜 문제를 해결할 수 있는가?** 를 고민합니다.
반복되는 작업은 자동화하고 문제의 본질에 집중합니다.

<br/>

### Languages

<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=Kotlin&logoColor=white"/> <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=OpenJDK&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>

### Frameworks & Libraries

<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white"/> 

### Databases

<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=PostgreSQL&logoColor=white"/> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white"/> <img src="https://img.shields.io/badge/Qdrant-D10C4D?style=flat-square&logo=Qdrant&logoColor=white"/>

### Infrastructure & Tools
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/> <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=Jira&logoColor=white"/>

### 🏢 Work Experience
* **WeInteract** | Backend Intern (2025.09 ~ 2025.11)
  * **[Tech-GPT](https://tech-gpt.ai/) (특허/논문 및 인재 탐색 AI 플랫폼 구축)** 
  * **하이브리드 검색 아키텍처 설계:** B-Tree 기반의 PostgreSQL(메타데이터/페이징)과 Qdrant(문서 원본)의 역할을 분리하여, 풀 스캔 병목을 해소하고 검색 응답 속도를 10초에서 3초 이내로 70% 최적화.
  * **대용량 데이터 파이프라인 최적화:** 1.2억 건의 데이터 전처리 시 SQLite WAL 튜닝과 메타데이터 인덱싱을 통해 I/O 시간복잡도를 O(N) -> O(1)로 단축.
  * **인프라 자동화 및 DX 개선:** Private Subnet 환경에서 Serverless Bridge(API Gateway + Cloud Functions)를 구축해 추가 비용 없이 CI/CD환경을 구축, 'Docs as Code' 기반의 문서화 표준을 수립해 팀 내 소통 비용 절약.

### 🚀 Projects
* **[CRAYON](https://www.crayon.land/) | 동아리 모집 프로세스 자동화 SaaS** (2024.07 ~ 2025.08) 
  * **비동기 아키텍처 도입:** Redis Queue와 Spring Event(@Async)를 활용해 무거운 외부 인프라 배포 작업을 분리, 동기식 처리의 병목을 해결하고 API 응답 속도를 95%(10초 -> 0.5초) 개선.
  * **동시성 제어:** 대규모 트래픽 발생 시의 Race Condition 버그를 막기 위해 DB 레벨의 복합 유니크 키(recruitment_id + user_id)를 적용하여 중복 지원 데이터 발생률을 0건.
  * **서버리스 정적 호스팅:** Next.js 컨테이너의 CPU 스파이크 문제를 S3 + CloudFront 정적 호스팅 파이프라인으로 전환하여, 평균 8초 이내로 배포하도록 구현.

* **Claude-Cli-Analytics | [cite_start]AI Agent 효율 시각화 대시보드 (Open Source)**
  * **AI 컨텍스트 엔지니어링:** Claude Code의 환각 현상을 제어하기 위해 구조화된 스펙 문서를 주입하는 환경을 설계하여, 기능 구현시 토큰 사용량을 15% 절감.
  * **DX 개선 사이클 구축:** 로컬에 저장된 Claude Code의 대화 기록을 파싱하여 AI의 스펙 문서 참조율과 Hit Rate를 시각화하는 대시보드 개발
---

## 🌱 Currently & Interests
* Human-in-the-loop 구조의 AI 활용에 관심이 많습니다.
* AI 도입에 따른 팀의 생산성 향상에 관심이 많습니다.
* 기초 CS를 집중해서 학습하고 있습니다.




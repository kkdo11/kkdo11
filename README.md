# 안녕하세요, 김도원입니다 👋

> **"고객의 모호한 문제를 작동하는 코드로 바꾸는 엔지니어"**

해커톤 대상, RAG 시스템, LLM 비용 최적화 프록시, ETL 파이프라인까지 —
**문제 정의부터 배포까지** 혼자서 끝까지 밀어본 경험을 반복해왔습니다.
AI 도구를 "사용"하는 것을 넘어 **개발 환경에 깊게 내재화**하는 데 관심이 많습니다.

- 🎯 **Interested in:** Forward Deployed Engineering, LLM Applications, Developer Experience
- 🛠 **Primary Stack:** Java/Spring Boot, Python/FastAPI, Kubernetes, PostgreSQL/pgvector, Redis
- 📧 kdw030612@gmail.com | 📝 [kdw.tistory.com](https://kdw.tistory.com)

---

## 🚀 Featured Projects

### 🧠 LLM-OPT — LLM API 비용 95.3% 절감 프록시
> **2-tier Semantic Cache | Python, FastAPI, Redis, HNSW**

LLM API 호출 비용 문제를 **의미 기반 캐싱 프록시**로 해결.

- **L1 (Redis Hash, 0.3ms):** 완전 일치 쿼리 즉시 응답
- **L2 (HNSW cosine similarity, 25.5ms):** 의미가 유사한 쿼리까지 캐시 히트
- **결과:** 실측 비용 **95.3% 절감**, False Positive Rate **0%**, 유닛 테스트 **151개**

→ "고객이 LLM 비용 감당 안 된다" 같은 실제 문제에 바로 투입 가능한 형태로 설계.

### 📚 MindGraph-AI — Java 기반 RAG 파이프라인
> **LangChain4j, pgvector, Qwen 2.5 14B (Ollama), RabbitMQ**

Spring Boot 생태계 안에서 **로컬 LLM + 벡터 DB**로 작동하는 RAG 시스템.

- 문서 임베딩 → pgvector 저장 → 유사도 검색 → Qwen 2.5 14B로 답변 생성
- **RabbitMQ 비동기 처리**로 임베딩 파이프라인 분리, 응답 레이턴시 단축
- 외부 LLM API 없이 **온프레미스에서 완결**되는 구조 (데이터 주권 필요한 고객 대응)

### 🏆 CueCode — 실시간 수어 통역 플랫폼
> **2025 서울 새싹 해커톤 대상 🥇 | Kubernetes(AKS) 기반 MSA | Role: DevOps & Backend Lead**

- **안정성:** API Gateway의 Header Propagation 재설계로 WebSocket 세션 손실 해결, 연결 안정성 100% 달성
- **DevOps:** Docker 레이어 캐싱 + Gradle 최적화로 CI/CD 빌드 시간 **30분 → 8분 (70% 단축)**
- **보안:** Spring Cloud Gateway 기반 중앙집중식 JWT 인증 아키텍처 구현

---

## 🤖 AI-Native Development

AI 도구를 단순히 "쓰는" 게 아니라 **개발 워크플로에 내재화**하는 작업을 계속해오고 있습니다.

- **Claude Code harness 커스터마이징:** `CLAUDE.md` 규약 · PreToolUse/PostToolUse/SessionEnd 훅 · 슬래시 커맨드 · `Learnings.md` 기반 세션 간 메모리 구축
- **로컬 LLM 추론 환경:** RTX 4080 Super + Ollama로 Qwen 2.5 14B 직접 운용 (RAG 프로젝트 백엔드)
- **현재 관심:** 에이전트 하네스의 품질 게이트 설계, 훅 기반 정적 분석 통합

---

## 🛠 Tech Stack

**Backend** Java 17 · Spring Boot 3.x · Python · FastAPI · JPA/Hibernate
**AI/Data** LangChain4j · pgvector · Ollama · HNSW · Redis
**Infra** Kubernetes (AKS) · Docker · GitHub Actions · AWS
**Database** PostgreSQL · MariaDB · MongoDB · Redis

---

## 🏅 Honors

- 🥇 **2025 서울 새싹 해커톤 대상** — 서울특별시 (2025.12)
- 🥉 **2025 공공 빅데이터 아이디어 공모전 장려상** — 전남정보문화산업진흥원 (2025.09)
- K-PaaS 전문가 교육 수료 (2025.09) · 정보처리산업기사 (2024.09) · SQLD (2023.04)

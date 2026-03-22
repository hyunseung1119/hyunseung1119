<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:6366f1&height=200&section=header&text=hyunseung&fontSize=50&fontColor=ffffff&fontAlignY=35&desc=AI%20Native%20Developer&descSize=18&descAlignY=55" width="100%" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hyun-seung-shin-a2a383383)
[![Blog](https://img.shields.io/badge/Tistory-FF5722?style=for-the-badge&logo=tistory&logoColor=white)](https://insight0263.tistory.com/)
[![Email](https://img.shields.io/badge/Email-03C75A?style=for-the-badge&logo=naver&logoColor=white)](mailto:dnclgk9@naver.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hyunseung1119)

</div>

<br>

> 모델을 만드는 것보다 **모델을 잘 쓰는 시스템**을 설계합니다.

<br>

## Tech Stack

<div align="center">

**AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-4B0082?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)

**Backend**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring_Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square)

**Data & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)

**Infra & Cloud**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/K8s-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_SAA-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</div>

---

## AI Engineering

<table>
<tr><td>

### [My_ClaudeCode_Skill](https://github.com/hyunseung1119/My_ClaudeCode_Skill) ![update](https://img.shields.io/badge/2026--03--22-updated-blue?style=flat-square)

> Claude Code 하네스 엔지니어링 셋업

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

2026 하네스 엔지니어링 방법론으로 AI 코딩 품질을 시스템적으로 보장하는 종합 설정 저장소. LangChain이 같은 모델로 벤치마크 52.8% > 66.5% 달성한 것과 동일한 접근.

**핵심 구성:**
- **30개** 전문 스킬 (RAG 2.0, Agentic Workflows, Security Audit 등)
- **23개** 자동 트리거 에이전트 (planner > code-reviewer > security-reviewer 자동 파이프라인)
- **14개** 훅 미들웨어 (안전 차단, 시크릿 감지, 자동 포맷, 타입 체크, doom loop 감지)
- **30개** CLI 커맨드 (`/plan`, `/tdd`, `/code-review`, `/multi-agent` 등)

**아키텍처:**
```
Agent Request → LocalContext → SafetyGuard → [Tool] → QualityGate → LoopDetect → Tracing → PreCompletion → Response
```

</td></tr>
<tr><td>

### [agent-verify](https://github.com/hyunseung1119/agent-verify)

> AI 생성 코드 자동 검증 엔진 — "코드가 의도대로 동작하는가?"

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![v0.3](https://img.shields.io/badge/v0.3-release-green?style=flat-square) ![coverage](https://img.shields.io/badge/coverage-86%25-brightgreen?style=flat-square)

SWE-bench를 통과한 PR의 ~50%가 실제 머지되지 않는 문제(METR Research, 2025)를 해결. PR Body / Commit Message / Spec에서 **의도(Intent)**를 추출하고, AST Diff로 코드가 그 의도를 실제로 달성했는지 검증.

**3가지 인터페이스:**
| Interface | Use Case |
|-----------|----------|
| **MCP Server** | Claude Code / IDE에서 실시간 검증 |
| **CLI** | `agent-verify check ./src` 로컬 실행 |
| **GitHub Action** | PR마다 자동 검증 CI 파이프라인 |

**기술:** tree-sitter AST 분석, Intent-Code Alignment 스코어링, 100K+ lines

</td></tr>
<tr><td>

### [forensic](https://github.com/hyunseung1119/forensic)

> Git 저장소 AI 코드 품질 감사 도구

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyPI](https://img.shields.io/badge/PyPI-published-blue?style=flat-square&logo=pypi&logoColor=white) ![HTML](https://img.shields.io/badge/Report-HTML-E34F26?style=flat-square)

2026년 공개 GitHub 커밋의 ~4%가 AI 작성 (연말 20% 전망). "우리 레포의 AI 코드 품질은 몇 점인가?"에 답하는 도구.

**기능:**
- `uvx git-forensic /path/to/repo` — 설치 없이 즉시 실행
- 커밋별 AI 작성 확률 + 품질 점수 산출
- 품질 트렌드 그래프 + 파일 타입별 분석 HTML 대시보드 리포트

</td></tr>
<tr><td>

### [My_Codex_Skill](https://github.com/hyunseung1119/My_Codex_Skill) ![star](https://img.shields.io/github/stars/hyunseung1119/My_Codex_Skill?style=flat-square)

> OpenAI Codex용 하네스 + 워크플로우 스킬

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

Claude Code와 동일한 하네스 엔지니어링 철학을 OpenAI Codex에 적용. 짧은 전역 규칙 + 도메인별 스킬 조합 방식.

</td></tr>
</table>

---

## AI Applications

<table>
<tr><td>

### [ML-DL](https://github.com/hyunseung1119/ML-DL)

> ML/DL 면접 합격 키트 — 주니어 엔지니어 체계적 학습

![Docs](https://img.shields.io/badge/35_files-7,062_lines-informational?style=flat-square)

3년차 미만 ML/DL 엔지니어가 면접에서 100점을 받기 위한 체계적 학습 저장소.

| 카테고리 | 주요 내용 |
|---------|---------|
| **수학 기초** | 선형대수, 미적분/최적화, 확률/통계 |
| **ML 기초+알고리즘** | 지도/비지도학습, 회귀, SVM, 트리앙상블, 클러스터링 |
| **DL 기초+아키텍처** | 역전파, CNN, RNN/LSTM, **Transformer**, GAN/VAE, Diffusion/MoE |
| **응용** | NLP (LLM 기초), CV (객체 탐지), MLOps (파이프라인, 서빙, 시스템 설계) |
| **면접 대비** | ML/DL 핵심 질문, 풀스택 ML, 코딩 챌린지 |

**특징:** 모든 문서에 ASCII 다이어그램 + 수학 공식 + Python 구현 + 면접 포인트

</td></tr>
<tr><td>

### [33_semu](https://github.com/hyunseung1119/33_semu)

> 종합소득세 AI 챗봇 — LangGraph 멀티 에이전트

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![lines](https://img.shields.io/badge/1M+-lines-orange?style=flat-square)

실제 세무(종합소득세, 부가가치세) 자동화 및 상담 챗봇 시스템.

**아키텍처:** React Frontend + FastAPI Backend + LangGraph AI Agent

**RAG 4단계 진화:**
| Version | 방식 |
|---------|------|
| V1 Basic | 기본 RAG |
| V2 TT-QA | 세무 특화 QA |
| V3 Hybrid | Hybrid Search (BM25 + Dense) |
| V4 Graph | Graph RAG |

</td></tr>
<tr><td>

### [Data_analysis](https://github.com/hyunseung1119/Data_analysis)

> Multi-Agent Decision System — AI 데이터 분석 의사결정

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

여러 AI 에이전트가 협업하여 데이터를 분석하고 의사결정을 지원하는 플랫폼. 데이터 수집 > 전처리 > 분석 > 시각화 > 인사이트 도출 자동화.

</td></tr>
</table>

---

## Backend & Architecture

<table>
<tr><td>

### [pulseQ](https://github.com/hyunseung1119/pulseQ)

> 선착순 이벤트 실시간 대기열 SaaS API

![Kotlin](https://img.shields.io/badge/Kotlin_2.0-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Spring](https://img.shields.io/badge/Spring_Boot_3.4-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![lines](https://img.shields.io/badge/237K+-lines-orange?style=flat-square)

티켓팅, 수강신청, 한정판 세일 등 순간 트래픽 폭주 문제를 해결하는 대기열 엔진.

| Layer | Stack |
|-------|-------|
| **Backend** | Kotlin 2.0, Spring Boot 3.4, WebFlux, Coroutines |
| **Data** | PostgreSQL 16, Redis 7 (Sorted Set + Distributed Lock) |
| **Messaging** | Apache Kafka (3 topics, event streaming) |
| **ML** | Python 3.12, FastAPI, LightGBM (봇 탐지) |
| **Frontend** | React 18, Vite, TanStack Query/Router, Tailwind v4, Recharts |
| **Monitoring** | Prometheus, Grafana |

**핵심 구현:** 분산 락 경합 해결, 원자적 카운터, RFC 9457 에러 처리, JWT Auth + Rate Limiting

</td></tr>
<tr><td>

### [BE_DEV](https://github.com/hyunseung1119/BE_DEV)

> 1억 트래픽 이커머스 MSA — 진화형 학습 프로젝트

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square) ![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)

Monolith에서 시작해서 직접 병목을 체험하고 MSA로 전환하는 "왜"를 체감하는 프로젝트.

```
Phase 0 기초 → Phase 1 모놀리식 → Phase 2 MSA/gRPC → Phase 3 EDA/Kafka → Phase 4 CQRS/Saga → Phase 5 CDC
```

**방법론:** 이론 > 트레이드오프 토론 > TDD 구현 > k6 부하테스트 사이클

</td></tr>
<tr><td>

### [Backend](https://github.com/hyunseung1119/Backend)

> Go + Node.js(TS) 대규모 트래픽 백엔드 & 인프라

![Go](https://img.shields.io/badge/Go_1.26-00ADD8?style=flat-square&logo=go&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![K8s](https://img.shields.io/badge/EKS-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![lines](https://img.shields.io/badge/63K+-lines-orange?style=flat-square)

| Layer | Stack |
|-------|-------|
| **API** | Gin/Echo + gRPC (Go), NestJS + Fastify (TS) |
| **Data** | PostgreSQL (Aurora) + sqlc, Redis, OpenSearch |
| **Messaging** | Kafka (MSK), SQS/SNS, EventBridge |
| **Infra** | Docker + EKS, Terraform + Terragrunt, ArgoCD (GitOps) |
| **Observability** | OpenTelemetry + Prometheus + Grafana |

**최종 프로젝트:** GrabTicket — 실시간 대기열 티켓 예약 시스템

</td></tr>
<tr><td>

### [digital_twin](https://github.com/hyunseung1119/digital_twin)

> P6IX SC 스마트 건설 디지털 트윈 플랫폼

![TypeScript](https://img.shields.io/badge/TypeScript_5.9-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React_19.2-61DAFB?style=flat-square&logo=react&logoColor=black) ![Three.js](https://img.shields.io/badge/Three.js_r182-000000?style=flat-square&logo=threedotjs&logoColor=white) ![lines](https://img.shields.io/badge/394K+-lines-orange?style=flat-square)

건설 현장의 실시간 모니터링, 4D BIM 시각화, AI 기반 안전 예측 플랫폼.

**핵심 기능:**
- 3D/4D BIM 시각화 (React Three Fiber, GLTF, PBR)
- AI 안전 위험 예측 + 일정 지연 분석 + 자원 최적화
- 드론/AMR 로봇 제어 (수동 조종 + 1인칭 탐색)
- IoT 센서 실시간 모니터링 + 비상 대응 시스템

</td></tr>
</table>

---

## Infra & Cloud

<table>
<tr><td>

### [AWS-SAA](https://github.com/hyunseung1119/AWS-SAA)

> AWS SAA-C03 학습 키트

![AWS](https://img.shields.io/badge/AWS_SAA--C03-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

정적 웹 기반 단계별 학습 도구. 기초 개념부터 SAA-C03 실전형 문제까지. TXT-driven exam drills로 반복 학습 지원.

</td></tr>
<tr><td>

### [infra](https://github.com/hyunseung1119/infra)

> Docker + Nginx + Kafka + Prometheus + Grafana 실습

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

PMIS Lab 인프라 실습 템플릿. Nginx reverse proxy > Django(Gunicorn) + 모니터링 스택.

</td></tr>
</table>

---

## CS Fundamentals

<table>
<tr><td>

### [My_CS](https://github.com/hyunseung1119/My_CS)

> CS 핵심 지식 — 면접 대비 + 실무 지식

Java/Spring을 제외한 CS 핵심 지식 체계적 정리. 모든 문서에 ASCII 다이어그램 + Python 구현 예시 + 면접 포인트 포함.

</td></tr>
</table>

---

## Approach

```
1. Harness Engineering  ── 모델을 바꾸지 않고 시스템으로 AI 코딩 품질을 올린다
2. Verifiable AI        ── AI가 만든 코드를 자동으로 검증하는 파이프라인을 구축한다
3. Build First          ── 이론보다 돌아가는 시스템을 먼저 만들고, 거기서 배운다
```

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hyun-seung-shin-a2a383383)
[![Blog](https://img.shields.io/badge/Tistory-FF5722?style=flat-square&logo=tistory&logoColor=white)](https://insight0263.tistory.com/)
[![Email](https://img.shields.io/badge/dnclgk9@naver.com-03C75A?style=flat-square&logo=naver&logoColor=white)](mailto:dnclgk9@naver.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:6366f1&height=100&section=footer" width="100%" />

</div>

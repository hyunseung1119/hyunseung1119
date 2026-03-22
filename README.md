<div align="center">

# hyunseung

**AI Native Developer**

모델을 만드는 것보다 **모델을 잘 쓰는 시스템**을 설계합니다.

[![GitHub](https://img.shields.io/badge/GitHub-hyunseung1119-181717?style=flat&logo=github)](https://github.com/hyunseung1119)

</div>

---

## Tech Stack

| Category | Technologies |
|----------|-------------|
| **AI/ML** | Python, LangGraph, LangChain, RAG, Ollama, ChromaDB, RAGAS |
| **Backend** | Go, Kotlin, Node.js(TS), FastAPI, Django, Spring |
| **Infra** | Docker, K8s, Terraform, Nginx, Kafka, Prometheus/Grafana |
| **Frontend** | React, Next.js, Three.js, TypeScript |
| **Cloud** | AWS (SAA), Vercel |

---

## AI Engineering

### [My_ClaudeCode_Skill](https://github.com/hyunseung1119/My_ClaudeCode_Skill)

> Claude Code 하네스 엔지니어링 셋업 — AI 코딩 품질을 시스템적으로 보장

`Python` `Shell`

2026년 하네스 엔지니어링 방법론을 Claude Code에 적용한 종합 설정 저장소. 모델을 바꾸지 않고 하네스만 개선해서 AI 코딩 품질을 올리는 접근.

- 30개 전문 스킬 + 23개 자동 트리거 에이전트 + 14개 훅 미들웨어
- 7대 미들웨어 파이프라인: 환경 주입 > 안전 차단 > 품질 검사 > 반복 감지 > 실행 추적
- 초보자용 튜토리얼 & 학습 가이드 포함

`latest` v4 — 12 hooks unified JSON output, execution tracing, session isolation

---

### [agent-verify](https://github.com/hyunseung1119/agent-verify)

> AI가 생성한 코드가 의도대로 동작하는지 자동 검증하는 엔진

`Python` `100,660 lines`

AI 코드를 사람이 일일이 검토하지 않아도 되는 자동 검증 파이프라인.

- MCP Server + CLI + GitHub Action 3가지 인터페이스
- tree-sitter 기반 코드 구조 분석
- 86% 테스트 커버리지

`latest` v0.3 — MCP Server, GitHub Action, bilingual README

---

### [forensic](https://github.com/hyunseung1119/forensic)

> Git 저장소에서 AI가 작성한 코드의 품질을 감사

`Python` `PyPI 배포`

2026년 공개 GitHub 커밋의 ~4%가 AI 작성. 이 도구로 AI 코드의 품질을 자동 감사.

- `uvx git-forensic`으로 즉시 설치/실행
- 커밋별 AI 작성 확률 + 품질 점수 산출
- HTML 리포트 생성

`latest` PyPI 퍼블리시 완료

---

### [My_Codex_Skill](https://github.com/hyunseung1119/My_Codex_Skill)

> OpenAI Codex용 하네스 + 워크플로우 스킬 저장소

`Python`

긴 전역 프롬프트 하나로 모든 것을 해결하는 대신, 짧은 전역 규칙과 도메인별 스킬을 조합하는 운영 방식.

---

## AI Applications

### [ML-DL](https://github.com/hyunseung1119/ML-DL)

> ML/DL 면접 합격 키트 — 주니어 개발자를 위한 체계적 학습 저장소

`Markdown` `35파일, 7,062줄`

3년차 미만 ML/DL 엔지니어가 면접에서 100점을 받기 위한 학습 자료.

- 9개 카테고리: 수학 기초 > ML > DL > NLP > CV > MLOps > 면접 대비
- 모든 문서에 ASCII 다이어그램 + 수학 공식 + Python 구현 + 면접 포인트
- 30개 실무 중심 모듈

---

### [33_semu](https://github.com/hyunseung1119/33_semu)

> 종합소득세 AI 챗봇 — LangGraph 기반 세무 상담 에이전트

`Python` `React` `1M+ lines`

실제 세무(종합소득세, 부가가치세) 자동화 및 상담 챗봇 시스템.

- React Frontend + FastAPI Backend 분리 아키텍처
- LangGraph 기반 멀티 에이전트 세무 상담
- Phase 4까지 진행 (리팩토링 + API 통합)

---

### [Data_analysis](https://github.com/hyunseung1119/Data_analysis)

> Multi-Agent Decision System — AI 기반 데이터 분석 및 의사결정 플랫폼

`Python` `JavaScript`

여러 AI 에이전트가 협업하여 데이터를 분석하고 의사결정을 지원하는 플랫폼.

---

## Backend & Architecture

### [pulseQ](https://github.com/hyunseung1119/pulseQ)

> 선착순 이벤트를 안전하고 공정하게 처리하는 실시간 대기열 SaaS API

`Kotlin` `TypeScript` `237K+ lines`

대규모 트래픽 환경에서 선착순 이벤트의 공정성을 보장하는 실시간 큐 시스템.

- 분산 락 경합 해결 + 원자적 카운터
- 프론트엔드 대시보드 (paginated events API)
- Quick Start 가이드 + 전체 아키텍처 문서

`latest` 분산 락 경합 해결 + 원자적 카운터

---

### [BE_DEV](https://github.com/hyunseung1119/BE_DEV)

> 1억 트래픽 이커머스 MSA 마스터 프로젝트

`Python` `Shell`

Monolith에서 시작해서 MSA > EDA > CQRS > CDC까지 단계적으로 진화하는 학습 프로젝트.

- Python CLI 진행 상황 뷰어
- Claude Code와 함께하는 대용량 트래픽 백엔드 아키텍처 실전 가이드

---

### [Backend](https://github.com/hyunseung1119/Backend)

> Go + Node.js(TS) 기반 대규모 트래픽 백엔드 & 인프라 학습

`Go` `HCL(Terraform)` `63K+ lines`

Phase 1~7 단계별 학습 코드 + 최종 프로젝트 GrabTicket (실시간 대기열 티켓 예약).

- Go 백엔드 + Terraform 인프라
- Observability (Prometheus/Grafana)
- AWS 서비스 연동

---

### [digital_twin](https://github.com/hyunseung1119/digital_twin)

> P6IX SC 스마트 건설 디지털 트윈 플랫폼

`TypeScript` `React` `Three.js` `394K+ lines`

React + Three.js 기반 3D 건설 현장 시각화 플랫폼.

---

## Infra & Cloud

### [AWS-SAA](https://github.com/hyunseung1119/AWS-SAA)

> AWS SAA-C03 학습 키트 — 정적 웹 기반 단계별 학습

`JavaScript` `Python`

초보자 기준으로 AWS 기초 개념부터 SAA-C03 실전형 문제까지 단계적으로 학습할 수 있는 정적 웹 기반 학습 도구.

- TXT-driven exam drills
- 단계별 학습 경로

---

### [infra](https://github.com/hyunseung1119/infra)

> Docker + Nginx + Kafka + Prometheus + Grafana 실습 템플릿

`Python` `TypeScript` `Dockerfile`

PMIS Lab 실습용 템플릿. Nginx reverse proxy > Django(Gunicorn) + 모니터링 스택.

---

## CS Fundamentals

### [My_CS](https://github.com/hyunseung1119/My_CS)

> CS 핵심 지식 저장소 — 면접 대비 + 실무 지식

`Markdown`

Java/Spring을 제외한 CS 핵심 지식을 체계적으로 정리. 모든 문서에 ASCII 다이어그램, Python 기반 구현 예시, 면접 포인트 포함.

---

## Approach

```
1. Harness Engineering — 모델을 바꾸지 않고 시스템으로 AI 코딩 품질을 올린다
2. Verifiable AI      — AI가 만든 코드를 자동으로 검증하는 파이프라인을 구축한다
3. Build First        — 이론보다 돌아가는 시스템을 먼저 만들고, 거기서 배운다
```

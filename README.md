<div align="center">

# 이성민 (Daniel Lee)

**AI Engineer & Full-Stack Developer**

고려대학교 정보대학 컴퓨터학과 23학번

<br>

[![Email](https://img.shields.io/badge/Email-hi.danleedev%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hi.danleedev@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-danlee--dev-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/danlee-dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-danlee--dev-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/danlee-dev/)

</div>

---

## About

AI Agent 시스템과 Multimodal AI를 연구하며, 실제 문제를 해결하는 서비스를 개발합니다.
현재 텍스트 기반 RAG에서 **Vision-Language Models (VLM)** 과 **Graph RAG**로 연구 영역을 확장하고 있습니다.

**Research Interests**
- Retrieval-Augmented Generation (RAG) & Graph RAG
- Multi-Agent Systems & AI Agents
- Vision-Language Models (VLM) & Multimodal AI

---

## Awards

<table>
<tr>
<td width="120" align="center"><strong>2025</strong></td>
<td>
<strong>최우수상 (1위)</strong> — KU 산학연계 캡스톤 디자인 경진대회<br>
<sub>DocScanner: Agentic RAG 기반 근로계약서 분석 AI</sub>
</td>
</tr>
<tr>
<td align="center"><strong>2025</strong></td>
<td>
<strong>최우수상 (정보통신기획평가원장상)</strong> — 제10회 SW인재페스티벌<br>
<sub>Smart Food Research Agent System: Multi-Agent RAG 시스템</sub>
</td>
</tr>
<tr>
<td align="center"><strong>2025</strong></td>
<td>
<strong>은상</strong> — 고려대학교 Uni-con 창업경진대회<br>
<sub>e:room: AI 룸메이트 매칭 및 사기 탐지 플랫폼</sub>
</td>
</tr>
</table>

---

## Publication

**[HCLT 2025] RAG와 Graph RAG 통합을 통한 다중 홉 복합 질의 검색 효율 향상**

> 제37회 한글 및 한국어 정보처리 학술대회
> **1저자** | RAG와 Graph RAG를 결합한 하이브리드 프레임워크를 제안하여 복합 질의에 대한 검색 효율을 최적화

<a href="https://github.com/danlee-dev/danlee-dev/blob/main/paper/Enhancing-Multi-Hop-Complex-Query-Retrieval-Efficiency-through-the-Integration-of-RAG-and-Graph-RAG.pdf">
<img src="https://img.shields.io/badge/PDF-논문_보기-B31B1B?style=flat-square&logo=adobeacrobatreader&logoColor=white" height="20"/>
</a>

---

## Featured Projects

### DocScanner — Hybrid RAG 기반 법률 AI

<a href="https://github.com/danlee-dev/252RCOSE48001"><img src="https://img.shields.io/badge/Repository-252RCOSE48001-181717?style=flat-square&logo=github&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Award-최우수상-FFD700?style=flat-square"/>

근로계약서를 AI로 분석하여 독소조항을 자동 탐지하고 법적 근거와 함께 개선안을 제시하는 시스템

| 구분 | 내용 |
|------|------|
| **핵심 기술** | Hybrid RAG (Elasticsearch + Neo4j), MUVERA 임베딩, Neuro-Symbolic AI |
| **분석 파이프라인** | HyDE → CRAG → RAPTOR → Constitutional AI → LLM-Judge (12단계) |
| **성능** | 위반 탐지 F1 +23.9% (vs GPT-4o), 체불액 산정 오차율 0% |
| **Tech** | Next.js, FastAPI, LangGraph, Gemini, OpenAI, KURE-v1 |

<br>

### IP-to-Portrait — AI 얼굴 합성 파이프라인

<a href="https://github.com/Diffusion-planet/ip-to-portrait"><img src="https://img.shields.io/badge/Repository-ip--to--portrait-181717?style=flat-square&logo=github&logoColor=white"/></a>

레퍼런스 이미지의 배경과 조명을 보존하면서 얼굴을 합성하는 End-to-End 파이프라인

| 구분 | 내용 |
|------|------|
| **핵심 기술** | SDXL Inpainting, IP-Adapter FaceID Plus v2, InsightFace, GFPGAN |
| **특징** | 실시간 Latent 미리보기, Gemini VLM 자동 프롬프트, 다중 GPU 병렬 처리 |
| **Tech** | Next.js, FastAPI, Celery, Redis, PyTorch, Diffusers, ONNX Runtime |

<br>

### GitDeck — 개발자 프로필 & 블로그 플랫폼

<a href="https://github.com/danlee-dev/git-deck"><img src="https://img.shields.io/badge/Repository-git--deck-181717?style=flat-square&logo=github&logoColor=white"/></a>

GitHub Profile README를 시각적으로 편집하고 개발자 블로그를 운영할 수 있는 통합 플랫폼

| 구분 | 내용 |
|------|------|
| **핵심 기능** | CodeMirror 6 실시간 에디터, 140+ 기술 뱃지, GitHub 양방향 동기화 |
| **소셜 기능** | 팔로우/팔로잉, 좋아요, 댓글, 실시간 알림 |
| **Tech** | Next.js 14, FastAPI, PostgreSQL, BlockNote, Gemini/OpenAI |

<br>

### Cardealo — 위치 기반 카드 혜택 추천

<a href="https://github.com/danlee-dev/cardealo"><img src="https://img.shields.io/badge/Repository-cardealo-181717?style=flat-square&logo=github&logoColor=white"/></a>

현재 위치 주변 매장에서 최적의 카드 혜택을 실시간으로 추천하는 모바일 앱

| 구분 | 내용 |
|------|------|
| **핵심 기능** | LBS 기반 실시간 추천, 매장별 최적 카드 분석 |
| **Tech** | React Native, FastAPI, PostgreSQL, Gemini API, Naver Cloud Platform |

<br>

### Smart Food Research Hub — Multi-Agent RAG 시스템

<a href="https://github.com/danlee-dev/crowdworks-multiagent-system"><img src="https://img.shields.io/badge/Repository-crowdworks--multiagent--system-181717?style=flat-square&logo=github&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Award-최우수상-FFD700?style=flat-square"/>

식품 산업을 위한 Multi-Agent RAG 시스템 (Crowdworks x KU 산학협력)

| 구분 | 내용 |
|------|------|
| **핵심 기술** | Multi-Agent Architecture, Graph DB, Elasticsearch |
| **협력** | 크라우드웍스 산학협력 프로젝트 |

---

## Tech Stack

<div align="center">

**Languages & Frameworks**

<img src="https://skillicons.dev/icons?i=python,pytorch,typescript,react,nextjs,fastapi&theme=light" />

<br><br>

**Database & Infrastructure**

<img src="https://skillicons.dev/icons?i=postgres,elasticsearch,redis,docker&theme=light" />

<br><br>

**AI/ML**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=for-the-badge)
![Graph RAG](https://img.shields.io/badge/Graph_RAG-008080?style=for-the-badge)
![Diffusers](https://img.shields.io/badge/Diffusers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

</div>

---

## Project Repositories

<table align="center">
<tr>
<td align="center" width="33%">
<a href="https://github.com/danlee-dev/ai-project-hub">
<img src="https://img.shields.io/badge/AI_Project_Hub-24292e?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<br><sub>AI 애플리케이션 & 서비스</sub>
</td>
<td align="center" width="33%">
<a href="https://github.com/danlee-dev/ai-paper-implementations">
<img src="https://img.shields.io/badge/AI_Paper_Impl-24292e?style=for-the-badge&logo=python&logoColor=white"/>
</a>
<br><sub>Multimodal 모델 구현</sub>
</td>
<td align="center" width="33%">
<a href="https://github.com/danlee-dev/cs-core-labs">
<img src="https://img.shields.io/badge/CS_Core_Labs-24292e?style=for-the-badge&logo=cplusplus&logoColor=white"/>
</a>
<br><sub>OS, 논리설계, 컴퓨터구조</sub>
</td>
</tr>
</table>

---

<div align="center">

**Currently Learning:** Large Multimodal Models (LMM), Graph Neural Networks, Advanced RAG

<br>

*"Building AI systems that change the world, one intelligent solution at a time."*

</div>

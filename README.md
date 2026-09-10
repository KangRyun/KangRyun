<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4C6EF5,100:0EA5E9&height=6" width="100%" />

<h1 align="center">이강륜</h1>
<p align="center"><b>Data · AI Engineer</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/%ED%95%9C%EB%82%A8%EB%8C%80%20%EB%B9%85%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%9D%91%EC%9A%A9%ED%95%99%EA%B3%BC-3.88%2F4.5-0B5FFF?style=flat-square" />
  <img src="https://img.shields.io/badge/SSAFY-15%EA%B8%B0-1428A0?style=flat-square" />
  <a href="mailto:kr9370@naver.com"><img src="https://img.shields.io/badge/Email-kr9370%40naver.com-03C75A?style=flat-square" /></a>
</p>

<br/>

## About

<table>
<tr>
<td width="50%" valign="top">

**만든 뒤 운영까지 가는 엔지니어**

- 한남대학교 공식 AI 챗봇 [hai.hannam.ac.kr](https://hai.hannam.ac.kr/)의 인프라·아키텍처를 맡아 **실서비스로 배포·운영 중**
- 단일 EC2에 **12컨테이너** 인프라와 Jenkins CI/CD를 단독 구축, 빌드 병목을 실측해 **10.7분 → 44초**
- Claude Code 멀티에이전트 하네스를 **3개 팀 프로젝트에 단독 설계**, CI 안에서 읽기 전용 헤드리스로 MR 리뷰 자동화

</td>
<td width="50%" valign="top">

**걸어온 길**

- 한남대학교 빅데이터응용학과 졸업 (2026.02, 3.88 / 4.5)
- 고등학교 문과계열에서 데이터·AI로 전공을 옮김
- SSAFY 15기 팀 프로젝트 3건 — 인프라·CI/CD와 AI 파이프라인 담당
- 학과 학생회장으로 11명 조직 운영, 중·고등학생 데이터 분석 멘토링

</td>
</tr>
</table>

<br/>

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,r,pytorch,tensorflow,django,fastapi,vue,kafka&perline=8" />
  <br/>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,elasticsearch,docker,linux,nginx&perline=8" />
  <br/>
  <img src="https://skillicons.dev/icons?i=jenkins,gitlab,prometheus,grafana,aws&perline=8" />
</p>

<p align="center">
  <sub>Claude Code · MCP(Notion·Jira) · OpenAI API · LLM/RAG · pgvector · FAISS · MinIO · Airflow · Spark · Flink · LightGBM · XGBoost · YOLO11 · Docker Compose · Blue-Green · k6</sub>
</p>

> **AI 네이티브 개발로 산출한 스택** — Spring Boot(Java 21·17) · Flutter(Dart) · React 19 + TypeScript · web3j
> Java와 Dart는 별도 학습 이력이 없고, Claude Code 하네스의 에이전트가 구현한 결과를 API 계약 검증·리뷰·테스트로 확인하는 방식으로 산출했습니다.

<br/>

## Projects

<table>
<tr>
<td width="50%" valign="top">

### 공연 티켓팅 · 공동 정산 플랫폼
<sub>SSAFY 특화 · 진행 중 · 인프라·CI + 서버 체인 모듈</sub>

스마트 컨트랙트 기반 티켓 예매·수익 정산

- Jenkins MR 빌드에 **Claude Code 읽기 전용 헤드리스 리뷰** 스테이지 구축
- 도입 첫 리뷰에서 봇이 자기 MR의 **취약점 2건 자체 검출**
- 체인 모듈 테스트 **76건 → 121건**

</td>
<td width="50%" valign="top">

### dodam(도담) · [Repo](https://github.com/KangRyun/Dodam)
<sub>SSAFY 공통 · 우수상 · 인프라·CI/CD 단독 + AI 서버</sub>

아동 정서 케어 AI 서비스

- Docker 빌드 **151s → 8.6s (-94%)**, 전체 파이프라인 **10.7분 → 44초 (-93%)**
- 12컨테이너 자체 호스팅 · Blue-Green 배포 · k6 부하테스트
- 팀 1,141커밋 중 **313건 (27%)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 한남대학교 공식 AI 챗봇 · [Live](https://hai.hannam.ac.kr/)
<sub>실서비스 운영 중 · 인프라·아키텍처</sub>

RAG 기반 학사 질의응답 챗봇

- Docker 마이크로서비스 아키텍처 설계
- FAISS 벡터 검색 ↔ 백엔드 연결 구조
- Prometheus · Grafana 실시간 모니터링, **공식 채널 배포**

</td>
<td width="50%" valign="top">

### 걸어서 대전속으로 · [Repo](https://github.com/KangRyun/fogwalk)
<sub>SSAFY 관통 · 2인 · 풀스택 단독 4기능</sub>

Fog of War 지도 탐험 + RAG 여행 추천

- pgvector 취향 벡터 + MMR 재랭킹, 추천 응답 **3.2s → 30ms**
- Elasticsearch Nori + LLM 태그 + 동의어 사전, 검색 "빵집" **0건 → 20건**
- 하네스 에이전트 5 · 스킬 6 단독 설계

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 대전 1호선 수요예측
<sub>공모전 대상 · 팀장</sub>

지하철 시간대별 승차 통행량 예측

- 외부 데이터 24개 변수 수집, 19개 선별
- 6개 모델 5-Fold 비교, RandomForest 채택
- **MAE 12.408 · 대상 (1위)**

</td>
<td width="50%" valign="top">

### LG Aimers 해커톤 · IoT 스마트팜
<sub>LG AI 연구원 7기 · KAIST 인턴</sub>

- 식음업장 매출 수량 시계열 예측 — LSTM + LightGBM 앙상블, **1,744명 중 55위 (상위 3.2%)**
- 센서 → MQTT → MySQL 실시간 파이프라인, DB 스키마 · Node-RED 대시보드 전 과정 주도

</td>
</tr>
</table>

<br/>

## Highlights

| | 수상 · 활동 | 기관 | 시기 |
|:-:|---|---|:-:|
| 🥇 | 지역사회 문제해결형 빅데이터/AI 활용 공모전 **대상** | 대전교통공사 | 2024 |
| 🏅 | SSAFY 2학기 공통 프로젝트 **우수상** (dodam) | 삼성전자 | 2026 |
| 🥉 | 지역사회 문제해결형 빅데이터/AI 활용 공모전 동상 | 한남대학교 | 2023 |
| 📈 | LG Aimers 7기 온라인 해커톤 **상위 3.2%** (1,744명 중 55위) | LG AI 연구원 | |
| 👥 | 빅데이터응용학과 제3대 학생회 '의지' 회장 | 한남대학교 | 2024 |

<br/>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KangRyun&theme=github_dark" />
    <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KangRyun&theme=github" alt="Top languages by repo" />
  </picture>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0EA5E9,100:4C6EF5&height=6" width="100%" />

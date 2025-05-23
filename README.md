# ⚾ 2022–2023 시즌 KBO 트렌드 데이터 분석 프로젝트

본 프로젝트는 한국 프로야구(KBO) 리그의 2022년, 2023년 시즌 데이터를 기반으로 **구단 성적과 팬 관심도 간의 관계**를 분석한 내용입니다.  
각 구단의 일자별 성적, 온라인 검색량, 관중 수 등의 데이터를 활용하여 팬들의 관심 변화와 관중 동원의 관계를 데이터 기반으로 해석했습니다.

---

## 📁 프로젝트 구성

- `KBO_트렌드_데이터_및_성적_분석.ipynb`: 데이터 수집, 전처리, 시각화 분석 포함된 핵심 노트북
- [프로젝트 관련 학술대회 논문](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11925983)

---

## 📊 주요 분석 내용

### 🔹 분석 목적
- 구단 순위와 온라인 검색량, 관중 수 간의 **상관관계 파악**
- **연승/연패 흐름**이 팬 관심도와 관중 수에 미치는 영향 확인
- 팬 관심도 데이터(검색량)를 활용한 **경기 트렌드 분석**

### 🔸 주요 분석 항목

| 분석 항목 | 설명 |
|-----------|------|
| 순위별 검색량 분석 | 순위가 낮은 팀일수록 검색량이 오히려 높은 패턴 확인 |
| 순위별 관중 수 분석 | 상위권 팀일수록 관중 수가 높은 경향 확인 |
| 연승/연패 vs 검색량 | 승패 흐름이 검색량에 미치는 영향 분석 (스피어만 상관계수 0.73, p=0.0158) |

---

## 🛠️ 사용 기술

- `Selenium` (동적 크롤링)
- `Pandas`, `Matplotlib`, `Seaborn` (데이터 처리 및 시각화)
- `CSV 병합`, `정규식`, `Label Encoding` 등 전처리 기법
- `스피어만 상관계수 분석` (상관성 정량화)

---

## 🔍 주요 시각화 예시

- Fig 1. 순위별 검색량 합계
- Fig 2. 순위별 관중 수 합계
- Fig 3. 연속 경기 흐름(연승/연패)과 검색량 평균

---

## ✨ 프로젝트 의의

- 성적 변화가 팬 관심도와 관중 수에 **실질적인 영향을 미친다는 데이터적 증거** 제공
- 향후 구단 마케팅 전략, 팬 소통 전략, 시즌 운영 방향 수립에 참고 가능
- 본 프로젝트는 후속 연구인 **관중 수 예측 모델 개발 프로젝트**의 기반이 되었습니다

---

## 🔄 다음 단계

이 프로젝트는 후속 연구인 관중 수 예측 모델 개발로 이어집니다.  
👉 [KBO 관중 수 예측 모델 개발 프로젝트 보러 가기](https://github.com/OhMinSuk/KBO-Ensemble-Learning)

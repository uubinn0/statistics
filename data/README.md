# 📊 Dataset: Cookie Cats A/B Test

## 📌 개요
모바일 게임 "Cookie Cats"에서 진행된 A/B 테스트 데이터입니다. 
👉 [Kaggle](https://www.kaggle.com/datasets/mursideyarkin/mobile-games-ab-testing-cookie-cats)

게임 진행 중 등장하는 gate 위치를 변경했을 때,
유저의 유지율(retention)에 미치는 영향을 분석하기 위한 실험입니다.

---

## 📊 데이터 개요

- 총 유저 수 : 90,189명
- 실험 그룹:
  - gate_30 : 약 44,700명
  - gate_40 : 약 45,400명

---

## 📂 컬럼 설명

| 컬럼명 | 설명 |
|--------|------|
| userid | 유저 고유 ID |
| version | 실험 그룹 (gate_30 / gate_40) |
| sum_gamerounds | 총 플레이 횟수 |
| retention_1 | 1일 후 유지 여부 (True/False) |
| retention_7 | 7일 후 유지 여부 (True/False) |

---
## 🧪 실험 설명

- **gate_30 (A 그룹)** : 30레벨에서 gate 등장
- **gate_40 (B 그룹)** : 40레벨에서 gate 등장

👉 가설:
gate 위치 변경이 유저 유지율에 영향을 줄 것이다.

---

## 🎯 분석 목표

- 두 그룹 간 retention 차이 비교
- 통계적 검정을 통한 유의미성 판단
- 신뢰구간 기반 결과 해석

---

## ⚠️ 참고 사항

- retention 데이터는 이진 변수 (True/False) → 비율 비교 분석 대상
- A/B 테스트 구조로 설계된 데이터
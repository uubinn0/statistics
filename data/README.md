# 📊 Dataset: Cookie Cats A/B Test

## 📌 개요
모바일 게임 "Cookie Cats"에서 진행된 A/B 테스트 데이터입니다. 
👉 [Kaggle](https://www.kaggle.com/datasets/mursideyarkin/mobile-games-ab-testing-cookie-cats)

게임 내 첫 번째 관문의 위치가 30레벨과 40레벨일 때,
retention에 어떤 차이가 있는지 알아보기 위한 A/B 테스트 결과 데이터.

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
| version | 실험 그룹 (대조군 : gate_30, 이동된 게이트 : gate_40) |
| sum_gamerounds | 설치 후 처음 14일 동안 플레이어가 플레이한 게임 라운드 수 |
| retention_1 | 설치 후 1일째 게임 플레이 여부 |
| retention_7 | 설치 후 7일째 게임 플레이 여부 |

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
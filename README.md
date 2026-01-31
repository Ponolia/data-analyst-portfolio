# 📊 Data Analyst Portfolio - 김기창

> **사용자 행동 데이터를 기반으로 비즈니스 인사이트를 도출하고 데이터 기반 의사결정을 수행한 분석 포트폴리오입니다.**

---

## 🚀 Project 1. E-commerce고객 세분화 및 CRM 전략 수립

![Analysis](https://img.shields.io/badge/Analysis-Pareto_&_Segmentation-green) ![Strategy](https://img.shields.io/badge/Strategy-Action_Plan-orange)

### 1️⃣ 개요 (Overview)
* **배경**: 브랜드 성장을 위해 핵심 고객을 정의하고, 한정된 마케팅 자원을 집중할 타겟팅 전략 필요
* **목표**: 파레토 분석을 통한 VIP 고객 식별 및 재구매 유도를 위한 CRM 액션 플랜 수립

### 2️⃣ 분석 워크플로우 (Workflow)
* **EDA**: 11만 건의 주문 데이터 정제 및 배송 완료(delivered) 건 필터링
* **Customer Segmentation**: 누적 매출 기여도 기반 고객 등급 분류 (VIP/우수/일반)
* **Insight**: 상위 **13% 고객이 전체 매출의 60%를 견인**하는 매출 쏠림 현상 확인

### 3️⃣ 시각화 및 전략 제안
| 분석 결과 (Visual) | 전략 제안 (Action Plan) |
| :---: | :--- |
| ![Pareto Curve](images/pareto_curve.png) | **VIP 락인**: 상위 5.2% 핵심 고객 대상 전용 혜택 제공 및 리워드 강화 |
| ![Customer Segments](images/customer_segments.png) | **타겟 마케팅**: 우수 고객 대상 재구매 유도 쿠폰 및 리텐션 캠페인 |
| ![Order Frequency](images/order_frequency.png) | **CRM 자동화**: 침구 교체 주기(6개월)에 맞춘 개인화 리마인드 알림톡 |

---

## 📉 Project 2. 카드 고객 이탈 예측 및 위험 등급 관리 (Churn Prediction)

![Model](https://img.shields.io/badge/Model-XGBoost_&_Ensemble-blue) ![Metric](https://img.shields.io/badge/Metric-Recall_0.9+-red)

### 1️⃣ 분석 요약
단순 예측을 넘어 **이탈 확률(Probability)**과 **거래 활동성 지표**를 결합하여, 실무에서 즉시 활용 가능한 **3단계 위험 관리 체계**를 수립했습니다.

### 2️⃣ 위험 등급 분류 체계 (Risk Segmentation)
| 등급 | 정의 및 기준 | 관리 전략 (Action Plan) |
| :--- | :--- | :--- |
| **🚨 High Risk** | 이탈 확률 > 35% & 활동성 지표 급감 | 즉각적인 복귀 프로모션 및 전담 케어 |
| **⚠️ Medium Risk** | 이탈 확률 25~35% & 하락 징후 포착 | 서비스 재방문 유도를 위한 맞춤형 알림 |
| **✅ Low Risk** | 이탈 확률 < 25% | 로열티 강화 및 교차 판매(Cross-selling) |

### 3️⃣ 실무 적용을 위한 SQL 로직 구현
* 모델의 예측 결과를 DB에 반영하여 마케팅 팀이 상시 추출할 수 있도록 **복합 조건 SQL 쿼리 로직** 설계. (최근 거래액, 비활성 월수, 이탈 확률 결합)

### 4️⃣ 기술 스택 및 성과
* **Model**: `XGBoost`, `Random Forest` (이탈 고객 재현율(Recall) 극대화)
* **Core Logic**: 데이터 기반 위험 고객 자동 분류 시스템 제안

---

## 🛠 Workflow & Methodology
`문제 인식` → `EDA` → `데이터 전처리` → `모델링/분석` → `전략 제안` → `기대 효과 산출`

---
**GitHub:** [github.com/Ponolia](https://github.com/Ponolia)

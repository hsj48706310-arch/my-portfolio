# 2026 차세대 생성형 AI 엔지니어 포트폴리오
> **홍서지 (Hong Seoji)** | AI Develop Engineer

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.12+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-Stateful_Agent-2E7D32?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OpenAI-GPT--4o--mini-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Pages-Live-222222?style=for-the-badge&logo=github&logoColor=white"/>
</div>

---

## 📌 Contact & Info
* 📧 **Email:** lictacco915@naver.com
* 📱 **Mobile:** 010.4870.6310
* 🌐 **Live Demo:** [GitHub Pages로 슬라이드 보기](https://hsj48706310-arch.github.io/my-portfolio/) *(GitHub 주소에 맞게 변경하여 사용하세요)*

---

## 🛠️ Core Tech Stack

| 분류 | 기술 스택 |
| :--- | :--- |
| **Language** | `Python 3.12+` |
| **LLM Engine** | `OpenAI GPT-4o-mini` |
| **Framework** | `LangGraph` (Stateful Workflow 설계), `LangChain`, `openai-sdk` |
| **Environment** | `python-dotenv` |
| **Interface** | `Streamlit`, `Jupyter` |

* **핵심 역량:** 상태 중심(Stateful) 에이전트 워크플로우 설계 및 순환형 파이프라인 구조화
* **프로젝트 기여도:** 2인 프로젝트 내 코어 추천 로직 및 비용 산출 알고리즘의 **90% 이상 전담 개발**

---

## 🚀 Project Context & Execution
### 💻 국내 여행 추천 LLM 에이전트 개발 프로젝트

#### 🚨 기존 문제 (Problem)
* **유연성 부족 및 비용 불명확:** 7개 지역과 10개 테마 조건이 실시간으로 결합되는 요구가 증가했으나, 복잡한 입력을 유연하게 반영하여 추천하고 정밀한 비용 계산 수식을 처리할 지능형 아키텍처가 부재했습니다.

#### 🎯 맡은 업무 (Role)
* **아키텍처 설계 & 엔진 개발:** LangGraph 프레임워크를 도입하여 복잡한 요구사항을 상태 단위로 격리했습니다. 프론트엔드 팀원과 연동할 데이터 규격(Spec)을 선제적으로 정의하고 백엔드 코어 엔진 개발을 총괄했습니다.

#### ⚙️ 진행 사항 (Action)
* **워크플로우 최적화 및 파이프라인:** `입력 수집 → 추천 → 비용 계산 → 요약`으로 이어지는 유연한 순환 파이프라인을 설계했습니다. `travel_data.py` 상에 정밀 수식을 구현하고, JSON 파싱 에러 방지를 위해 Fallback 메커니즘을 연동하여 시스템 예외 처리를 견고히 했습니다.

---

## 📈 Project Outcome (Result)

### 💡 수동 계획 대비 50% 이상의 효율 개선
* **인터페이스 최적화:** 복잡했던 여행 계획 수립 과정을 단 7단계의 자동화 입력 인터페이스로 단축 완료했습니다.
* **시스템 가용성 확보 (Crash-free):** 네트워크 및 LLM API의 순간적인 오류 발생 환경 속에서도 다운타임 없이 안정적으로 가동되는 파이프라인을 실현하며 프로젝트 완성도를 입증했습니다.

---
*혁신을 꿈꾸는 개발자, 홍서지였습니다. 감사합니다.*

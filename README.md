# 🚀 UPSTA: AI Interview Assistant

> **"당신의 지원서 속에 숨겨진 날카로운 질문을 찾아냅니다."**

**UPSTA**는 사용자의 자기소개서(PDF)를 정밀 분석하여 맞춤형 면접 질문을 생성하고, 실전 같은 모의 면접 경험을 제공하는 **Intelligent AI Agent**입니다. Upstage Solar LLM과 Document AI, 그리고 LangGraph를 결합하여 단순한 챗봇 그 이상의 정교한 흐름 제어를 구현했습니다.

---

## ✨ Key Features

| 기능 | 상세 설명 |
| --- | --- |
| 📄 **Resume Deep Parsing** | **UpstageDocumentParseLoader**를 통해 복잡한 레이아웃의 PDF 지원서에서도 텍스트와 구조 정보를 정확하게 추출합니다. |
| 🧠 **Intelligent Q&A** | 업로드된 문서의 맥락을 파악하여 기술적 역량(Technical), 행동 지표(Behavioral), 도메인 지식에 특화된 질문 리스트를 생성합니다. |
| 🔄 **State-driven Workflow** | **LangGraph**를 기반으로 설계되어 사용자의 입력에 따라 '일반 대화'와 '서류 분석' 모드를 유연하게 전환합니다. |
| ☀️ **Solar-Powered Intelligence** | Upstage의 최신 **solar-pro3** 모델을 사용하여 한국어 면접 상황에 최적화된 고성능 답변을 제공합니다. |

---

## 🛠️ Tech Stack

UPSTA는 최첨단 AI 기술 스택을 활용하여 구축되었습니다.

* **LLM Engine**: `Upstage solar-pro3` (High-performance Korean language processing)
* **Document AI**: `Upstage Layout Analysis` (Accurate PDF parsing)
* **Agent Framework**: `LangGraph` (State-aware conversational flow)
* **Orchestration**: `LangChain`

---

## 💡 How it Works

1. **Analyze**: 사용자가 PDF 형식의 자기소개서를 업로드합니다.
2. **Extract**: Document AI가 문서 내의 주요 프로젝트 및 경험 데이터를 구조화합니다.
3. **Generate**: Solar-pro3 모델이 각 경험에 대한 예상 압박 질문과 직무 관련 질문을 뽑아냅니다.
4. **Interview**: 추출된 질문을 바탕으로 AI와 실시간 모의 면접을 진행하며 피드백을 받습니다.

---

> **Note**
> UPSTA는 단순한 키워드 매칭이 아닙니다. 문맥(Context)을 이해하는 차세대 면접 파트너입니다.

---

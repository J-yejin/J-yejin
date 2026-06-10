![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=300&section=header&text=Develop,%20Growth&fontSize=50)

## Hi there 👋

### 안녕하세요, 우상향을 바라보며 성장하는 개발자 정예진입니다.

데이터로 문제를 구조화하고, AI 기술이 실제 서비스 안에서 작동하도록 구현하는 데 관심이 많습니다.  
금융, 공공, 헬스케어, 보안 도메인 프로젝트에서 **데이터 분석, 모델링, AI Agent 설계, OCR/RAG/LLM Worker 구현, API 연동**까지 경험했습니다.

문제를 단순히 기술로 해결하는 데 그치지 않고,  
사용자가 실제로 체감할 수 있는 서비스 경험으로 완성하는 개발자로 성장하고 있습니다.

---

## 🧭 About Me

- 🎓 서울시립대학교 경영학부 / 빅데이터분석학 복수전공
- 🏫 삼성청년 SW·AI 아카데미 SSAFY 14기
- 💡 관심 분야: AI Agent, LLM Application, RAG, Vision AI, Data Analysis
- 🧩 강점: 문제 구조화, 서비스 흐름 설계, AI 기능 구현, 프로젝트 리딩
- 📌 목표: 데이터와 AI를 기반으로 사용자 문제를 해결하는 서비스형 개발자

---

## 💻 Tech Stack

AI Agent 설계부터 OCR·RAG 기반 LLM 서비스 구현, 데이터 분석 및 Vision AI 모델 개발까지 수행할 수 있습니다.  
주요 기술 스택은 아래와 같습니다.

### AI / LLM / Agent

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-4B5563?style=flat&logo=readme&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen-111827?style=flat&logo=ollama&logoColor=white)
![Gemma](https://img.shields.io/badge/Gemma-4285F4?style=flat&logo=google&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

### Backend / API

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=spring&logoColor=white)

### Data / ML / Vision

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) 
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) 
![XGBoost](https://img.shields.io/badge/XGBoost-FF8000?style=flat&logo=xgboost&logoColor=white) 
![LightGBM](https://img.shields.io/badge/LightGBM-000000?style=flat&logo=lightgbm&logoColor=lightgreen)
![YOLO](https://img.shields.io/badge/YOLO-111827?style=flat&logo=yolo&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

### DB / Infra / Tools

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white) 
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)

---

## 🧩 Main Projects

### 🏦 Zu.D — 주택담보대출 상담/심사 자동화 AI 기반 DSS

> 주택담보대출 상담·사전심사의 서류 판독, 내규 검토, 심사 결과 설명을 자동화한 AI 기반 의사결정지원시스템

- **Role**: PM & AI
- **Tech**: Qwen2.5-VL, Qwen3, RAG, FastAPI, Kafka, vLLM, OpenCV
- **What I did**
  - Qwen VL 기반 OCR Worker 구조 설계
  - 16종 주택담보대출 심사 서류 분류 및 핵심 정보 추출
  - RAG가 반환한 내규 조항 ID와 원문을 심사 기준으로 고정
  - LLM 심사 결과를 승인 / 검토 / 반려 형태로 구조화
  - XAI 리포트 생성을 위한 JSON 응답 형식 설계
- **Result**
  - 자체 테스트 문서 10건 기준 OCR 분류 및 정보 추출 정확도 100%
  - 문서 처리 약 30초, 심사 및 리포트 생성 약 40초
  - SSAFY 특화 프로젝트 우수상 3위 수상
 

[![Github](https://img.shields.io/badge/github-repo-blue?logo=github)](https://github.com/A406-HLY)

<br/>

### 🤖 ARMI — 병상 환자를 위한 AI-Agent 기반 로봇팔 보조 서비스

> 병상 환자의 음성 요청을 AI Agent가 해석해 물품 전달, 간호사 호출, 의료진 전달사항 기록으로 연결하는 병상 보조 서비스

- **Role**: PM & AI
- **Tech**: FastAPI, LangGraph, Spring 연동, YOLO11m-seg
- **What I did**
  - FastAPI / LangGraph 기반 AI Agent 서버 설계 및 구현
  - 환자 발화 intent 분류 및 실행 가능한 payload 정규화
  - LLM이 직접 실행하지 않고 actionPlan만 생성하는 Controlled Agent 구조 설계
  - ROBOT_ACTION, NURSE_CALL, STAFF_MESSAGE, INFO_REQUEST 실행 흐름 분리
  - YOLO11m-seg 데이터셋 구축 및 모델 학습 실험
- **Result**
  - 핵심 intent 처리 정확도 96.5%
  - YOLO11m-seg Mask mAP50 0.667, Mask mAP50-95 0.510

[![Github](https://img.shields.io/badge/github-repo-blue?logo=github)](https://github.com/JoKong98/ARMI-project)

<br/>

### 🦾 행가래 — 재활 보조 AIoT 서비스

> 재활 환자의 동작 수행 상태를 AI Vision으로 측정하고, 엣지 환경 적용 가능성을 검토한 재활 보조 서비스

- **Role**: PM & AI Vision
- **Tech**: YOLO11-pose, PyTorch, MMPose, TensorRT, Jetson
- **What I did**
  - AI Vision 모델 연구 및 YOLO11m-pose 파인튜닝
  - 재활 동작 분석을 위한 21개 keypoint 데이터셋 구축
  - COCO17 / HICO dataset 기반 pseudo labeling 수행
  - Jetson 환경 적용을 위한 경량화
- **Result**
  - mAP50 0.988, mAP50-95 0.925, Precision 0.982
  - SSAFY 공통 프로젝트 우수상 1위 수상

[![Github](https://img.shields.io/badge/github-repo-blue?logo=github)](https://github.com/Hang-ga-rae/aiot-rehab-assistant)

<br/>

### 🔐 숨결 — AI 기반 개인정보 3단 탐지·비식별화 서비스

> 다양한 문서 포맷과 자연어 요청을 지원하는 개인정보 탐지 및 비식별화 서비스

- **Role**: PM & Frontend
- **Tech**: Regex, NER, Qwen3, Figma
- **What I did**
  - 개인정보 탐지 흐름 및 서비스 UX 설계
  - Regex 기반 정형 개인정보 스키마 설계
  - 도메인별 권장 항목, 전체 선택/해제, 자연어 요청 입력 UI 설계
  - 탐지 결과 및 비식별 리포트 화면 구성
- **Result**
  - 사전에 정의되지 않은 민감정보와 자연어 기반 비식별 요청 처리 서비스 구체화
  - 제3회 KISIA 정보보호 개발 해커톤 장려상 수상

<br/>

### 📊 창업기업 고용성과 연구 프로젝트

> 창업기업 고용성과를 분석하고, 질적 고용 지표와 혁신기업 분류 기준을 개선한 정책 데이터 분석 프로젝트

- **Role**: Data Analyst
- **Tech**: Python, SQL, Sentence Embedding, Ko-SRoBERTa, Cosine Similarity
- **What I did**
  - 참여기업 정보, 고용정보 5만 건, 법인기업 DB 100만여 건 전처리
  - 기업명 정규화, 사업자번호 검증, 협약기간 변환, 중복기업 식별
  - 순고용, 사업 전후 변화, 고용 리텐션, 유사기업 대비 지표 설계
  - Ko-SRoBERTa 기반 혁신기업 분류 개선 로직 제안
- **Result**
  - 질적 고용성과 측정을 위한 신규 지표 설계
  - 혁신기업 분류 정확도 약 40% 개선

<br/>

### 💳 소BINGO — 신한금융그룹 빅데이터 해커톤

> 카드 소비 데이터를 분석해 고객군별 맞춤형 소비 빙고 서비스를 제안한 금융 데이터 해커톤 프로젝트

- **Role**: Team Leader & Service Planner
- **Tech**: Python, K-means Clustering, Data Analysis
- **What I did**
  - 카드 소비 데이터 전처리 및 업종 재분류
  - 군집분석 기반 고객 페르소나 정의
  - 소비 패턴 기반 맞춤형 앱 서비스 기획
- **Result**
  - 신한카드 부문 우수상 수상

---

## 🏆 Awards

- SSAFY 특화 프로젝트 우수상 3위 · 2026
- SSAFY 공통 프로젝트 우수상 1위 · 2026
- 제3회 KISIA 정보보호 개발 해커톤 장려상 · 2025
- 첨단분야 혁신융합대학 서포터즈 대상, 교육부 장관상 · 2023
- 신한금융그룹 빅데이터 해커톤 신한카드 부문 우수상 · 2023

---

## 🎖️ Certification

- 빅데이터분석기사 · 2025.07
- OPIc IH · 2025.04
- 사회조사분석사 2급 · 2024.06
- SQLD · 2023.04
- ADsP · 2022.09

---

## 📚 Education

### **University of Seoul**  
#### Business Administration / Big Data Analytics  
2020.03 – 2025.08  
#### 🚩 GPA: 4.12 / 4.5 
#### 🧪 주요 활동 
- 마케팅학회 ICON (학회장): IMC 전략, 산학협력 프로젝트 수행
- 빅데이터 혁신융합대학 서포터즈 (교육부장관상 수상)
- 비즈니스 애널리틱스 프로그램 우수상 : 썸트렌드를 활용한 SNS 데이터 분석 및 인사이트 도출
- 서울권 경영대학 연합학술제 아카데미쿠스 대상: 공급망 회복탄력성의 정의 및 강화 방안 분석 연구

<br/>

### **UNLV Engineering International Program**  
#### University of Nevada, Las Vegas  
#### Machine Learning & Deep Learning program / Survive Analysis project  
2024.06 - 2024.07

<br/>

### **Samsung Software AI Academy For Youth, SSAFY 14th**  
2025.07 – 2026.06

---

## 📫 Contact

<a href="mailto:yejimy0524@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white"/>
</a>
<a href="mailto:yejin2202@naver.com">
  <img src="https://img.shields.io/badge/Naver_Mail-03C75A?style=flat-square&logo=naver&logoColor=white"/>
</a>

<br/>

[![Notion Portfolio](https://img.shields.io/badge/Portfolio-Notion-000000?style=flat-square&logo=notion&logoColor=white)](https://app.notion.com/p/AI-Data-Analysist-Portfolio-bbf533b0e12a82db98c8810b84389890?source=copy_link)

<h1 align="center">Hi 👋 I'm Hong Jeonghui</h1>

<p align="center">
  🤖 AI Explorer | 📊 Data Analyst in Progress | 💡 Always Learning <br/>
  📍 Based in Seoul, Korea <br/>
  📫 Contact: jngpop123@gmail.com
</p>

---

### 💁 소개

- 🎓 SSAFY 14기 이수 중입니다.
- 🤖 저는 **시각 정보와 언어 정보를 함께 이해하는 AI 시스템**에 큰 흥미가 있습니다.  
- 📊 데이터 분석, LLM, 멀티모달 AI에 꾸준히 관심을 가지고 학습하고 있습니다.   
- 🛠️ 최근에는 **YOLO**, **GPT API**, **EfficientNet**, **LSTM** 등을 활용한 프로젝트들을 진행했습니다.  


---

### ⚙️ Tech Stack

#### 🧠 AI / Deep Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8%2Fv11-111111?style=flat)
![EfficientNet](https://img.shields.io/badge/EfficientNetV2S-00BFFF?style=flat)
![LSTM](https://img.shields.io/badge/LSTM-FFA500?style=flat)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

#### 🤖 LLM / AI Engineering
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-FF69B4?style=flat)
![Agent System](https://img.shields.io/badge/LLM%20Agent-6A5ACD?style=flat)
![RAG](https://img.shields.io/badge/RAG%20Pipeline-20B2AA?style=flat)

#### 🌐 Backend / API
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat)
![REST API](https://img.shields.io/badge/REST%20API-02569B?style=flat)
#### 🐳 DevOps / Deployment
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

#### ⚡ Edge / Hardware
![Jetson](https://img.shields.io/badge/Jetson%20Orin%20Nano-76B900?style=flat&logo=nvidia&logoColor=white)

---

### 🗂️ 주요 프로젝트
- 🛒 **AI Smart Cart – 실시간 객체 탐지 기반 무인 결제 시스템**  
  마트 환경에서 카트 내부 상품을 **실시간으로 인식**하고  
  줄을 서지 않고 바로 결제할 수 있도록 설계한 Edge AI 프로젝트입니다.  

  - 🧠 모델: YOLOv8s / YOLO11s 성능 비교 후 YOLO11s 최종 채택  
  - 📊 mAP50 약 0.95, mAP50-95 약 0.58  
  - ⚡ Jetson Orin Nano 환경에서 실시간 추론 최적화  
    - Avg Latency 약 505ms  
    - FPS 약 1.98  
  - 🔬 MLflow 기반 실험 관리 (epoch, augmentation, lr 등 비교 기록)  
  - 🧩 Mosaic / Mixup / LR 튜닝을 통한 성능 개선  
  - 🐳 Docker 기반 학습·추론 서버 분리 구조  
  - 🌐 FastAPI로 AI 서버–백엔드 API 연동  

 > 모델 학습부터 MLflow 기반 실험 관리, FastAPI 추론 서버 구축,
 > Jetson Orin Nano 환경 최적화까지 전체 구조를 직접 설계하고 구현했습니다.

- 🤖 **AI Interview Agent**  
  GPT 기반 모의 면접 시스템으로,  
  이력서 분석 → 질문 전략 생성 → 답변 평가 → 후속 질문까지 자동으로 실행합니다.

- 🌦️ **Emergency Predictor**  
  기상 데이터와 지역 특성을 활용해  
  119 구조·구급 신고량을 예측하는 모델입니다.
  해당 프로젝트는 대회 평가에서 우수성을 인정받아 입선되었습니다.

- 👩‍🍳 **AI Chef – 이미지 기반 레시피 추천 시스템**  
  음식 이미지에서 재료를 YOLO로 감지하고,  
  감지된 재료 조합으로 GPT가 레시피를 자동 생성하는 멀티모달 프로젝트입니다.  
  - 🥬 1,900장의 이미지, 38개 재료 종류로 학습  
  - 🧠 모델: YOLOv11, mAP 약 0.78  
  - 💡 재료 기반 자동 레시피 생성  
  - 🔗 ChatGPT 연동으로 다양한 요리 제안 가능

- 🖼️ **Image Caption Generator**  
  이미지를 입력하면 자연스러운 문장을 생성하는 딥러닝 모델입니다.  
  - 📌 Flickr8k(8,000장 × 5캡션) 데이터셋 기반  
  - 🧠 EfficientNetV2S로 특징 추출 + LSTM으로 문장 생성  
  - ⚙️ Custom tokenizer, 패딩, 입력 구조 직접 구현  
  - 🚧 입력 불일치, 마스킹, 시퀀스 처리 오류 등을 해결하며 모델 안정화  
  - ✨ BLEU Score 기반 평가로 성능 개선  
  - 🎯 Dropout, EarlyStopping 등으로 자연스러운 문장 출력


---


<p align="center">
  <img src="https://komarev.com/ghpvc/?username=hongjeonghee&style=flat-square&color=blue" alt="Visitor Badge"/>
</p>

# 🎙️ Speech AI Research Engineer

**실시간 다국어 음성 처리 · 다국어 언어감지(LID) · 생성형 AI**

[![Email](https://img.shields.io/badge/Email-choi.debugs.y@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:choi.debugs.y@gmail.com)
[![Notion](https://img.shields.io/badge/Notion-Coming_Soon-000000?style=flat-square&logo=notion&logoColor=white)]()

---

## 🧑‍💻 About Me

기업부설연구소에서 **음성인식(STT)** 분야의 연구개발을 담당하고 있으며, **실시간 다국어 STT**와 **다국어 언어감지(LID)** 를 메인으로 연구하고 있습니다.
부가적으로 **생성형 AI 챗봇 / RAG 시스템**의 설계와 구축, 운영까지 경험했습니다.

- 🎙️ **Speech** — Selvy STT(상용) · Faster Whisper(CTranslate2 변환 실시간 모델) · Cloud STT(ElevenLabs, Google STT) 기반 실시간 다국어 STT 시스템 구축·운영
- 🌐 **LID** — ECAPA-TDNN 기반 7개 언어 감지 모듈 개발 (영어 / 일본어 / 중국어 / 러시아어 / 태국어 / 인도네시아어 / 베트남어) 및 LID 모델 자체 파인튜닝 경험
- 🤖 **Generative AI** — 사용자 질문 의도 분류 → RAG 답변 / sLLM(Gemma3:12b, Ollama) 분기 로직 기반 QnA 챗봇 설계·구축

---

## 🔬 Currently Working On

- 🚀 **다국어 STT 고도화** — 도메인 환경에서의 인식 정확도 / 실시간 지연시간 / 언어 전환 안정성 개선
- 🎤 **WavLM 기반 화자인식** — 도메인 음성 데이터로 파인튜닝한 WavLM을 활용하여 화자 분리·식별 정밀도 향상
- 🧠 **Cumulative LID 아키텍처 설계 및 개발** — ECAPA-TDNN 임베딩 기반 누적 언어식별 구조 설계 (단일 세그먼트 LID의 불안정성을 보완하기 위해 화자·채널 단위 프로파일과 시간 가중 누적 히스토리를 결합)

---

## 🏭 Production / Deployment

실제 콜센터 현장에 다국어 실시간 STT 시스템을 도입하여 **구축 → 운영 → 고도화**까지 전 과정을 담당했습니다.

- 🇰🇷 **외교부 영사콜센터** — 한국어 / 영어 실시간 STT 시스템 도입 및 구축, 운영
  - Selvy STT(상용 S/W) + Faster Whisper(Self-hosted) 하이브리드 파이프라인
  - VAD → STT → LID → 코드스위칭 화면 출력까지 end-to-end 운영
- 🧭 **한국관광공사 1330 관광안내콜센터** — 8개 언어(한국어 / 영어 / 일본어 / 중국어 / 러시아어 / 태국어 / 인도네시아어 / 베트남어) 실시간 STT 시스템 도입 및 구축, 운영
  - Selvy STT(상용 S/W) or Faster Whisper(Self-hosted) + Cloud STT(ElevenLabs / Google STT) 하이브리드 파이프라인
  - 통역사 중계 통화(상담원 / 통역사 / 외국인 화자 동시 처리) 환경 대응
  - 실시간 화자/언어 감지 + 누적 LID 기반 안정적 다국어 STT 전사
- 🤗 **Hugging Face 모델 파인튜닝 및 운영 적용**
  - 콜센터 도메인 음성 데이터를 활용해 **Whisper / WavLM / ECAPA-TDNN** 등 사전학습 모델을 파인튜닝
  - 학습 → 평가(EER 등) → 변환(CTranslate2) → 실시간 추론 서버 배포까지 일괄 진행

---

## 🛠️ Tech Stack

#### 🥇 Main — *실무 메인*

`Languages & Frameworks`

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=coffeescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

`Speech / ML`

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Selvy STT](https://img.shields.io/badge/Selvy_STT_(상용)-1A73E8?style=for-the-badge&logoColor=white)
![Faster Whisper](https://img.shields.io/badge/Faster_Whisper-412991?style=for-the-badge&logoColor=white)
![CTranslate2](https://img.shields.io/badge/CTranslate2-1F6FEB?style=for-the-badge&logo=cplusplus&logoColor=white)
![SpeechBrain](https://img.shields.io/badge/SpeechBrain_(ECAPA--TDNN)-FF6F00?style=for-the-badge&logoColor=white)
![Silero VAD](https://img.shields.io/badge/Silero_VAD-2E7D32?style=for-the-badge&logoColor=white)
![WavLM](https://img.shields.io/badge/WavLM_(Fine--tuning)-9C27B0?style=for-the-badge&logoColor=white)
![NVIDIA CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

#### 🥈 Sub — *실무 활용 경험*

`Cloud STT / Generative AI`

![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=for-the-badge&logo=elevenlabs&logoColor=white)
![Google Cloud STT](https://img.shields.io/badge/Google_Cloud_STT-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama_(Gemma3)-000000?style=for-the-badge&logo=ollama&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge&logo=databricks&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_(pgvector)-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logoColor=white)

`Audio / Data / Frontend`

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![librosa](https://img.shields.io/badge/librosa-4D77CF?style=for-the-badge&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

`Build / Ops`

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Rocky Linux](https://img.shields.io/badge/Rocky_Linux-10B981?style=for-the-badge&logo=rockylinux&logoColor=white)
![Gitea](https://img.shields.io/badge/Gitea-609926?style=for-the-badge&logo=gitea&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

#### 🤖 AI Tools

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=for-the-badge&logo=githubcopilot&logoColor=white)
![Gemini CLI](https://img.shields.io/badge/Gemini_CLI-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)

---

![snake gif](https://github.com/LegSmith/LegSmith/blob/output/github-contribution-grid-snake.svg)

<h1 align="left">💻GitHub Analytics</h1>
<p>
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=LegSmith&show_icons=true&locale=en&theme=tokyonight" alt="LegSmith" />&nbsp;
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=LegSmith&show_icons=true&locale=en&layout=compact&theme=tokyonight" alt="LegSmith" />
</p>

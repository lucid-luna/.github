<p align="center">
  <img src="assets/Logo.png" width="240" alt="L.U.N.A. Logo" />
</p>

<h1 align="center">L.U.N.A.</h1>
<h3 align="center">Lucid Undulation Neural Aether</h3>
<p align="center">당신과 함께 숨 쉬는 인공지능 디지털 비서</p>

<p align="center">
  <a href="#소개">소개</a> •
  <a href="#구성-리포지토리">구성 리포지토리</a> •
  <a href="#기능">기능</a> •
  <a href="#설치-및-실행">설치 및 실행</a> •
  <a href="#라이선스">라이선스</a>
</p>

---

## 🧭 소개

**L.U.N.A.**는 실시간으로 사용자와 소통하며, 데스크탑 상에서 **VRM 기반 AI 비서**처럼 동작하는 인공지능 시스템입니다.  
음성 인식(STT), 자연어 처리(LLM), 음성 합성(TTS), 감정 분석, 모션 제어, OSC 송신 등을 통합적으로 수행하며,  
사용자와 감성적으로 연결된 새로운 형태의 **디지털 피규어** 경험을 제공합니다.

---

## 📂 구성 리포지토리

| 리포지토리         | 설명                                                                 |
|------------------|----------------------------------------------------------------------|
| [`luna-core`](https://github.com/lucid-luna/luna-core)     | 백엔드 핵심 기능: STT, TTS, LLM, 감정 분석, OSC 통신 등                              |
| [`luna-client`](https://github.com/lucid-luna/luna-client) | Unity 기반 프론트엔드: VRM 모델 표현, 사용자 인터페이스 등                         |
| [`luna-plugins`](https://github.com/lucid-luna/luna-plugins) | 확장 가능한 LLM 플러그인 모듈: 검색, 계산기, 메모, 미디어 제어 등                  |
| [`luna-models`](https://github.com/lucid-luna/luna-models) | L.U.N.A.에서 사용할 커스텀 AI 모델 개발 및 파인튜닝 코드                            |

---

## ✨ 기능

- 🗣️ **STT + TTS**: Whisper 기반 음성 인식 및 자연스러운 음성 합성
- 💬 **LLM 연동**: 다양한 GPT/LLM 기반 질의응답 및 상황 반응
- 🎭 **감정 분석**: 문맥 기반 감정/톤 분류 및 얼굴 표정 전환
- 🪞 **VRM 렌더링**: Unity에서 캐릭터를 실시간으로 표현
- 🛰️ **OSC 지원**: VRChat, VMC 등 외부 소프트웨어 연동 가능
- 🔌 **플러그인 시스템**: 도구 실행, 검색, 미디어 제어 등 확장 기능

---

## 🚀 설치 및 실행

🛠️ 각각의 리포지토리 `README.md`를 참고하세요. 기본적으로는 다음 단계를 따릅니다:

```bash
# 1. 코어 백엔드 클론
git clone https://github.com/lucid-luna/luna-core.git
cd luna-core

# 2. 종속성 설치 및 실행
pip install -r requirements.txt
python main.py

# 3. 클라이언트(Unity) 실행
# luna-client 디렉토리에서 Unity로 열기

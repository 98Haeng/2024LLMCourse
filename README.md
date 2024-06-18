# 2024 명지대학교 LLM 과정 코드 자료

## 1일차
- 간단한 LLM 모델 한국어 파인튜닝 실습 코드를 진행하였습니다.
- gemma_finetuning_koalpaca.ipynb파일은 MacBook에서는 제대로 완벽하게 돌아가지 않습니다. (사유 : bitsandbytes가 Mac에서 정상적으로 지원되지 않습니다.)

## 2일차
- Ollama 실습 및 Langchain을 이용한 ChatOllama를 활용한 LLM, OpenAI 코드 실습, 간단한 Streamlit을 활용한 코드 실습을 진행했습니다.

## 3일차

## 주의사항
- 파일명에 Colab이라고 존재하는 파일들은 반드시 Colab안에서만 실행해야 합니다.
- ngrok 코드를 실행하는 부분은 코랩에서만 진행합니다. (일반적인 코드에서는 필요 업습니다.)

## 필수 설치 프로그램
Ollama -> Ollama 코드를 구현하기 위해 필요합니다. (https://www.ollama.com/)

- 작동 방식
    - 터미널(Mac, Linux) or CMD(Window)을 열어서 모델 다운로드를 진행합니다
    - ollama pull modelname or ollama run modelname (최초 1회만 다운로드 됩니다.)
    - 코드 실행을 위해 pull을 수행한 터미널 및 CMD를 코드 실행 동안 절대 닫지 말아야 합니다.


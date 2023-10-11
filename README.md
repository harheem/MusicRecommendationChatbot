# Music Recommendation Chatbot
An interactive chatbot that empathizes with users and recommends songs based on their mood or situation, built using the text_generation library and Gradio UI.


### 📌 소개

Music Recommendation Chatbot은 사용자의 기분이나 상황에 따라 음악을 추천해주는 대화형 챗봇입니다. 
`text_generation` 라이브러리와 `Gradio UI`를 사용하여 구현되었습니다. 

이 코드는 [ChatGPT: Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) 강의에서 제공된 코드를 기반으로 작성되었습니다.
음악 추천을 위한 텍스트 임베딩 과정에서는 한국어 문장 임베딩을 위한 모델([jhgan/ko-sroberta-multitask](https://huggingface.co/jhgan/ko-sroberta-multitask))과 멜론 데이터셋을 활용합니다.
해당 프로젝트에는 이 부분이 없으므로 사용한 Retriever에 대한 내용은 [이 코드](https://github.com/junejae/music-recsys-feat-kollama2/blob/main/retriever.ipynb)에서 확인할 수 있습니다.


### 🚀 시작하기
필요한 라이브러리 설치

```
pip install text_generation gradio
```

Inference Endpoints 생성
이 코드를 실행하기 위해서는 [Inference Endpoints](https://ui.endpoints.huggingface.co)를 생성해야 합니다.
이 프로젝트에서는 [kfkas/Llama-2-ko-7b-Chat](https://huggingface.co/kfkas/Llama-2-ko-7b-Chat) 모델로 엔드포인트를 생성하였습니다.

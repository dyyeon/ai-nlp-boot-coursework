# NLP Study Repository

<p align="center">
  <img src="ms.png" alt="멋쟁이사자처럼 AI NLP 부트캠프" width="720">
</p>

멋쟁이사자처럼 AI NLP 부트캠프 실습 코드들을 기록했습니다.

## 📌 260629_nlp_project
- NLP 수업 중 실습 1, 2

## 📌 260630_sentiment_benchmark
- NLTK movie_reviews로 LSTM 감성 분석 모델 학습 후 GLUE SST-2로 fine-tuning 및 test 예측
- 사전학습 BERT 기반 아마존 리뷰 벤치마크 — 평점(overall)과 도움됨(helpful) 수치를 멀티태스크 회귀로 예측 (feature engineering, layer freezing, early stopping)

## 📌 260701_seq2seq_attention
- 숫자 시퀀스 뒤집기 태스크로 Vanilla Seq2Seq와 Bahdanau Attention 성능 비교 (GRU, random search 하이퍼파라미터 튜닝)
- 일본어→한국어 번역으로 Seq2Seq vs Seq2Seq+Attention 비교 과제

## 📌 260702_transformer_translation
- PyTorch `nn.Transformer`로 직접 구성한 Ko→En 번역 모델 — Byte-level BPE 토크나이저 직접 학습, unlikelihood training, beam search/repetition penalty 등 디코딩 전략별 BLEU 비교

## 📌 260703_BERT_LoLA
- ImageNet 사전학습 ViT-B/16에 LoRA를 순수 PyTorch로 구현·적용하여 Oxford-IIIT Pet 37개 품종 분류로 fine-tuning

## 📌 260706_GPT
- Llama 3.1-8B base 모델과 instruct 모델을 동일한 프롬프트로 비교
- TRL로 SFT->RM->PPO로 이어지는 RLHF 전 과정을 돌려보고, 보상 점수를 통해 모델이 점점 더 친절한 답변을 내도록 학습

## 📌 260707_GPT
- CoT(Chain-of-Thought)기법에 대한 조사 및 정리, 활용하여 두 가지 문제를 다양한 CoT기법을 해결해 본 후 팀원들과 비교
- Naive RAG의 문제점을 찾아보고 개선 사항 설계하기

## 📌 260708
- 한국동서발전 주관, 풍력발전량 예측 AI 경진대회 참가
- 기상예보 데이터 기반 풍력발전량 예측 AI 모델 개발 (https://dacon.io/competitions/official/236727/overview/description)

## 📌 260709
- 코딩 테스트
- 실전 프로젝트 오리엔테이션
- 프로젝트 팀 구성 및 주제 선정

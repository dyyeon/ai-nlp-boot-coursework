# NLP Study Repository

<p align="center">
  <img src="ms.png" alt="멋쟁이사자처럼 AI NLP 부트캠프" width="720">
</p>

멋쟁이사자처럼 AI NLP 부트캠프 실습 코드들을 기록했습니다.

## 📌 260629_nlp_project
- nlp_proj1.ipynb : NLP 수업 중 실습 1
- nlp_proj2.ipynb : NLP 수업 중 실습 2

## 📌 260630_sentiment_benchmark
- lstm_sentiment_sst2.ipynb : NLTK movie_reviews로 LSTM 감성 분석 모델 학습 후 GLUE SST-2로 fine-tuning 및 test 예측
- bert_review_rating.ipynb : 사전학습 BERT 기반 아마존 리뷰 벤치마크 — 평점(overall)과 도움됨(helpful) 수치를 멀티태스크 회귀로 예측 (feature engineering, layer freezing, early stopping)

## 📌 260701_seq2seq_attention
- seq2seq_vs_attention_toy.ipynb : 숫자 시퀀스 뒤집기 태스크로 Vanilla Seq2Seq와 Bahdanau Attention 성능 비교 (GRU, random search 하이퍼파라미터 튜닝)
- seq2seq_ja_ko_translation.ipynb : 일본어→한국어 번역으로 Seq2Seq vs Seq2Seq+Attention 비교 과제

## 📌 260702_transformer_translation
- transformer_ko_en_translation.ipynb : PyTorch `nn.Transformer`로 직접 구성한 Ko→En 번역 모델 — Byte-level BPE 토크나이저 직접 학습, unlikelihood training, beam search/repetition penalty 등 디코딩 전략별 BLEU 비교

## 📌 260703_BERT_LoLA
- vit_lora_finetuning.ipynb : ImageNet 사전학습 ViT-B/16에 LoRA를 순수 PyTorch로 구현·적용하여 Oxford-IIIT Pet 37개 품종 분류로 fine-tuning

## 📌 260706_GPT
- Llama 3.1-8B base 모델과 instruct 모델을 동일한 프롬프트로 비교
- TRL로 SFT->RM->PPO로 이어지는 RLHF 전 과정을 돌려보고, 보상 점수를 통해 모델이 점점 더 친절한 답변을 내도록 학습

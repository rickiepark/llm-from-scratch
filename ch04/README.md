# 4장: 밑바닥부터 GPT 모델 구현하기

&nbsp;
## 예제 코드

- [01_main-chapter-code](01_main-chapter-code)에는 4장의 코드와 연습 문제 해답이 포함되어 있습니다. 

&nbsp;
## 보너스 자료

- [02_performance-analysis](02_performance-analysis) contains optional code analyzing the performance of the GPT model(s) implemented in the main chapter
- [03_kv-cache](03_kv-cache) implements a KV cache to speed up the text generation during inference
- [07_moe](07_moe) explanation and implementation of Mixture-of-Experts (MoE)
- [ch05/07_gpt_to_llama](../ch05/07_gpt_to_llama) contains a step-by-step guide for converting a GPT architecture implementation to Llama 3.2 and loads pretrained weights from Meta AI (it might be interesting to look at alternative architectures after completing chapter 4, but you can also save that for after reading chapter 5)

## Attention Alternatives

&nbsp;

<img src="https://sebastianraschka.com/images/LLMs-from-scratch-images/bonus/attention-alternatives/attention-alternatives.webp">

&nbsp;

- [04_gqa](04_gqa) contains an introduction to Grouped-Query Attention (GQA), which is used by most modern LLMs (Llama 4, gpt-oss, Qwen3, Gemma 3, and many more) as alternative to regular Multi-Head Attention (MHA)
- [05_mla](05_mla) contains an introduction to Multi-Head Latent Attention (MLA), which is used by DeepSeek V3, as alternative to regular Multi-Head Attention (MHA)
- [06_swa](06_swa) contains an introduction to Sliding Window Attention (SWA), which is used by Gemma 3 and others
- [08_deltanet](08_deltanet) explanation of Gated DeltaNet as a popular linear attention variant (used in Qwen3-Next and Kimi Linear)

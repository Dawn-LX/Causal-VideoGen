Official Implementation of ViD-GPT [ViD-GPT: Introducing GPT-style Autoregressive
Generation in Video Diffusion Models]()

our code is build upon open-sora (https://github.com/hpcaitech/Open-Sora), with the following features
 - autoregressive long video generation, i.e., generating subsequent clips conditioned on last frames of
previous clip
 - calsual generaion (by causal temporal attention)
 - frame as prompt, i.e., the conditional frames serve as prompt (the prefix of token sequence)
 - kv-cache boosted inference, i.e., autoregressive generation without the redundant computation of overlapped frames.

The code is preparing

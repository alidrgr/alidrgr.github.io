---
hide:
  - navigation
title: Monthly Logs
date:
  created: 2025-02-05
  updated: 2025-03-06
---

# Logs

These are monthly logs of things that have piqued my interest.

## February 2025

* You probably have not thought about the complexity beneath your phone's calculator app. Well, [here](https://twitter.com/ChadNauseam/status/1890889465322786878) is an interesting thread about Hans Boehm's efforts in designing a calculator app for Android. There is also a paper[^6] by Boehm himself. 

* [MIT CS 6.S184](https://diffusion.csail.mit.edu/) is a course on denoising diffusion models and flow matching, with lecture notes available online.

* "Mechanistic Understanding and Mitigation of Language Model Non-Factual Hallucinations"[^7] identifies two distinct mechanisms behind hallucinations in LLMs: Knowledge Enrichment hallucinations, occurring in early to middle MLP layers, and Answer Extraction hallucinations, caused by middle to late self-attention heads.

## January 2025

* [Escaping The Flatland](https://space.ong.ac/escaping-flatland) is an interesting essay on career trajectory that describes how mimetic desires and peer pressure define and shape a few constrained 'planes of legibility' in the space of things one could consider viable and valuable in life.

* "Attention Satisfies"[^1], an ICLR 2024 paper, frames hallucination detection in LLMs as a constraint satisfaction problem and trains a probe on attention values. The idea of zero-knowledge hallucination detection in LLMs appears to be a promising avenue for further research. Two important baselines I've found in this line of research are "SelfCheck-GPT"[^2] and "SAPLMA (Internal States)"[^3].

* The [Theory Group](http://theory.cs.berkeley.edu/) at UC Berkeley has a pleasantly simple webpage, made even better by its archive of past course offerings.

* With DeepSeek-R1 surprising everyone with its performance, reading the report[^4] felt essential. The DeepSeek-AI group had previously published another paper before DeepSeek-R1 named "DeepSeekMath"[^5], which I discovered thanks to a YouTube [video](https://youtu.be/bAWV_yrqx4w?si=nZsZmd7WKXyYIbwQ) by [Yannic Kilcher](https://www.youtube.com/@YannicKilcher).

* [Solving Problems the Clojure Way](https://youtu.be/vK1DazRK_a0?si=ueiXAR_87ctyeAWK) is a well-structured talk. Watching a functional refactor in action while hearing the thought process behind it was quite clarifying.

## References
[^1]: M. Yuksekgonul et al., “Attention Satisfies: A Constraint-Satisfaction Lens on Factual Errors of Language Models,” presented at the The Twelfth International Conference on Learning Representations, Oct. 2023. Accessed: Oct. 21, 2024. [Online]. Available: https://openreview.net/forum?id=gfFVATffPd
[^2]: P. Manakul, A. Liusie, and M. Gales, “SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models,” in Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing, H. Bouamor, J. Pino, and K. Bali, Eds., Singapore: Association for Computational Linguistics, Dec. 2023, pp. 9004–9017. doi: 10.18653/v1/2023.emnlp-main.557.
[^3]: A. Azaria and T. Mitchell, “The Internal State of an LLM Knows When It’s Lying,” in Findings of the Association for Computational Linguistics: EMNLP 2023, H. Bouamor, J. Pino, and K. Bali, Eds., Singapore: Association for Computational Linguistics, Dec. 2023, pp. 967–976. doi: 10.18653/v1/2023.findings-emnlp.68.
[^4]: DeepSeek-AI et al., “DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning,” Jan. 22, 2025, arXiv: arXiv:2501.12948. doi: 10.48550/arXiv.2501.12948.
[^5]: Z. Shao et al., “DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models,” Apr. 27, 2024, arXiv: arXiv:2402.03300. doi: 10.48550/arXiv.2402.03300.
[^6]: H.-J. Boehm, “Towards an API for the real numbers,” in Proceedings of the 41st ACM SIGPLAN Conference on Programming Language Design and Implementation, in PLDI 2020. New York, NY, USA: Association for Computing Machinery, Jun. 2020, pp. 562–576. doi: 10.1145/3385412.3386037.
[^7]: L. Yu, M. Cao, J. C. Cheung, and Y. Dong, “Mechanistic Understanding and Mitigation of Language Model Non-Factual Hallucinations,” in Findings of the Association for Computational Linguistics: EMNLP 2024, Y. Al-Onaizan, M. Bansal, and Y.-N. Chen, Eds., Miami, Florida, USA: Association for Computational Linguistics, Nov. 2024, pp. 7943–7956. doi: 10.18653/v1/2024.findings-emnlp.466.

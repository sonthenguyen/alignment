# Training-Free Alignment

Hands-on tutorials on aligning language models at inference time without modifying model weights.

**Authors:** Son The Nguyen, Tommy Cheng, Theja Tulabandhula

<p align="center">
  <img src="assets/training-free-alignment-as-cherry-on-top.png" alt="Training-free methods as a cherry on top of training-based methods to align LLMs" width="700"/>
  <br/>
  <em>Training-free methods as a cherry on top of training-based methods to align LLMs. Image created by Son The Nguyen using the Sloggoth meme with Nano Banana 2.</em>
</p>

---

## About This Repository

Training-Free Alignment is a collection of hands-on educational tutorials on methods for aligning language models at inference time without modifying model weights.

The collection is authored and curated by Son The Nguyen, Tommy Cheng, and Theja Tulabandhula. The tutorials cover both established methods from the broader research literature and original research contributions by the tutorial authors.

Methods developed by third parties are attributed to their original authors and publications within the corresponding notebooks. Inclusion of a method in this repository does not imply that the Training-Free Alignment authors originated that method.

Original research contributions by the tutorial authors are identified explicitly, including MEMETRON, which is described separately below.

---

### NAIRR 2026 Tutorial

<p align="center">
  <a href="https://youtu.be/KkhyuMftyYw?si=8pUt2SY9lNvPcdYN">
    <img src="https://img.youtube.com/vi/KkhyuMftyYw/maxresdefault.jpg" alt="Watch the tutorial on YouTube" width="700"/>
  </a>
</p>

---

### Prompt Engineering

Zero-shot, few-shot, chain-of-thought, and automatic prompt engineering.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sonthenguyen/alignment/blob/main/prompt_engineering_for_training_free_alignment.ipynb)

---

### Guided Decoding

Standard decoding strategies (greedy, beam search, temperature, top-k/top-p) and guided decoding with logits processors for hallucination prevention.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sonthenguyen/alignment/blob/main/guided_decoding_for_training_free_alignment.ipynb)

---

### Response Engineering

Static strategies (Best-of-N, self-consistency) and iterative strategies (Reflexion, Mixture-of-Agents) for improving response quality at inference time.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sonthenguyen/alignment/blob/main/response_engineering_for_training_free_alignment.ipynb)


## Authors

| Name | Links |
|------|-------|
| Son The Nguyen | [Website](https://sonthenguyen.com) · [X](https://x.com/son_thenguyen) · [LinkedIn](https://www.linkedin.com/in/sonthenguyen/) |
| Tommy Cheng | [LinkedIn](https://www.linkedin.com/in/tommyckcheng/) |
| Theja Tulabandhula | [Website](https://theja.org/) · [X](https://x.com/TTulabandhula) · [LinkedIn](https://www.linkedin.com/in/theja-t/) |

## Original Research: MEMETRON

**MEMETRON: Memetic Response Optimizer for Reward-Guided Post-Decoding Optimization of Large Language Models**  
Son The Nguyen and Theja Tulabandhula  
*Transactions on Machine Learning Research (TMLR), 2026*

MEMETRON formulates reward-guided post-decoding response optimization as a discrete black-box optimization problem and introduces GENETRON and ANNETRON for iterative response optimization.

- [TMLR / OpenReview](https://openreview.net/forum?id=QRW8OGn3vb)
- [arXiv](https://arxiv.org/abs/2506.08643)

### BibTeX

```bibtex
@article{nguyen2026memetron,
  title={MEMETRON: Memetic Response Optimizer for Reward-Guided Post-Decoding Optimization of Large Language Models},
  author={Son The Nguyen and Theja Tulabandhula},
  journal={Transactions on Machine Learning Research},
  year={2026},
  url={https://openreview.net/forum?id=QRW8OGn3vb}
}
```

## License

Original tutorial text, slides, figures, diagrams, and other educational content created for this repository are licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](LICENSE-CONTENT), unless otherwise noted.

Original source code authored specifically for this repository is licensed under the [MIT License](LICENSE-CODE).

Third-party methods are attributed to their original authors and sources. Third-party libraries, dependencies, code, figures, datasets, and other materials remain subject to their respective licenses, copyright terms, and attribution requirements.

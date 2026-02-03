# Zero-Shot Statistical Tests for LLM-Generated Text Detection and Attribution using Finite Sample Concentration Inequalities

This repository contains the official code to replicate experiments from our paper:



🔗 **Live Demo**: [Try it on Hugging Face Spaces](https://huggingface.co/spaces/tararad/Liketropy-LLM-Detector)


---

## 📁 Contents

| Notebook | Description |
|----------|-------------|
| `Whiteboxdetection.ipynb` | Runs statistical detection tests using access to the LLM (white-box setting). |
| `Whiteboxattribution.ipynb` | LLM Attribution: identifies the generating model among two sets of candidates. |
| `Blackbox_adverserial.ipynb` | Tests black-box detection and robustness of our detection against adversarial attacks. |

All experiments were run on RunPod (B200) and use Hugging Face models and datasets where applicable.

---

## 🧪 How to Run

Each notebook is fully self-contained and includes:

- Installation and environment setup (in the first cells)
- Data loading and preparation
- Full experiment code with results

💻 **No setup beyond running the notebook cells is required** — all dependencies are installed inline.

---

## 📥 Data

Most datasets used in the experiments are downloaded programmatically from 🤗 Hugging Face.

However:

> **If you'd like to run the WritingPrompts experiments**, you'll need to download the WritingPrompts dataset manually from:  
> 🔗 [https://github.com/facebookresearch/WritingPrompts](https://github.com/facebookresearch/WritingPrompts)

Place the downloaded data in the following path:
data/writingPrompts/

Portions of this code are adapted from DetectGPT, available at:
https://github.com/eric-mitchell/detect-gpt/tree/main

We thank the authors of DetectGPT for open-sourcing their codebase.



---

## 🧾 Citation

If you use this code or build upon our work, please cite:

```bibtex
@article{radvand2025zero,
  title={Zero-Shot Statistical Tests for LLM-Generated Text Detection using Finite Sample Concentration Inequalities},
  author={Radvand, Tara and Abdolmaleki, Mojtaba and Mostagir, Mohamed and Tewari, Ambuj},
  journal={arXiv preprint arXiv:2501.02406},
  year={2025}
}


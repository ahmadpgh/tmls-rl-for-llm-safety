# Reinforcement Learning for LLMs to Enhance Safety — TMLS Workshop

A Hands-on Colab notebook for applying RLHF (Reinforcement Learning from Human Feedback) to improve the safety of large language models (LLMs) using the [SafeEdit dataset](https://huggingface.co/datasets/zjunlp/SafeEdit).

---

## Features

- **Colab-ready**: All code runs on free Colab GPU (T4).
- **Data**: Uses SafeEdit — pairs of unsafe and safe generations.
- **Pipeline**:
  - Data upload & exploration
  - Supervised fine-tuning (SFT) with PEFT/LoRA
  - Reward model training (preference-based)
  - PPO-based RLHF (with reward model)
  - Evaluation & analysis

---

## Quick Start

1. **Clone or open in Colab**  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

2. **Upload SafeEdit dataset**  
   Download from [Google Drive link](https://drive.google.com/file/d/1eJ7UzxS9KlOeIpCH_ABk1HqXX3ELDxMl/view?usp=drive_link).  
   Upload the ZIP when prompted.

3. **Run all cells**  
   Follow the notebook steps for data prep, model training, and evaluation.

---

## Requirements

- Python 3.x
- [Colab](https://colab.research.google.com/) (recommended)
- Packages: `transformers`, `datasets`, `trl`, `peft`, `bitsandbytes`, `wandb`, `torch`

---

## Data

- **SafeEdit**: Paired adversarial prompts/questions with unsafe and safe model generations.
- **Usage**: Educational/research only. Please comply with dataset terms.

---

## Citation

If you use this notebook or dataset, please cite:

- SafeEdit: [https://arxiv.org/abs/2403.14472](https://arxiv.org/abs/2403.14472)

---

## License

For educational use only. See dataset and code licenses for details.

---

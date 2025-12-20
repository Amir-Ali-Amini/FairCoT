# FairCoT  
Fairness-aware prompting for text-to-image generation using Chain-of-Thought reasoning.

**Authors:** Zahraa Al Sahili, Ioannis Patras, and Matthew Purver  
📄 **Paper:** FairCoT: Enhancing Fairness in Text-to-Image Generation via Chain-of-Thought Reasoning with Multimodal Large Language Models (Findings of EMNLP, 2025)

---

## 🔍 Overview  
This repository contains code, prompt templates, and data for **FairCoT**, a lightweight framework that uses **multimodal LLM reasoning** to generate **fairer text prompts** for text-to-image models.

---

## 📁 Repository Structure

| Folder | Description |
|--------|-------------|
| `FairCoT_Dataset/` | Data used for experiments and evaluation |
| `Prompt_Templates/` | Prompt templates used for fairness-aware generation |
| `Train_CoT/` | Scripts/files for building CoT demonstrations (training phase) |
| `inference_CoT/` | Inference pipeline for applying FairCoT to new prompts/tasks |
| `code/` | Core utilities and helper code |

---

## 📚 Citation  
If you use this repository, please cite:

```bibtex
@inproceedings{alsahili2025faircot,
  title={FairCoT: Enhancing Fairness in Text-to-Image Generation via Chain-of-Thought Reasoning with Multimodal Large Language Models},
  author={Al Sahili, Zahraa and Patras, Ioannis and Purver, Matthew},
  booktitle={Findings of the Association for Computational Linguistics: EMNLP},
  year={2025}
}

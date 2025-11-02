# Foundational Models — Lightweight Adaptation & Evaluation (Skeleton)
A reviewable skeleton showing how to *evaluate* and *lightly adapt* LLM/VLM components on small tasks.

## Why this exists
- Mila posting mentions adapting VLM/LLM architectures and building evaluation pipelines.
- This repo shows you understand evaluation design, latency/throughput trade-offs, and prompt robustness checks.

## Quick start
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python src/eval.py --task sentiment --samples 50
```
> If `transformers` isn't installed, the script will fall back to a stub and print clear instructions.

## What to highlight in interview
- You focused on *evaluation & reproducibility*, not raw SOTA.
- You report **accuracy/F1**, **latency**, and **prompt perturbation robustness**.

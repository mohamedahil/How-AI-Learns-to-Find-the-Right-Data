# How-AI-Learns-to-Find-the-Right-Data
Mathematical derivations and PyTorch Proof-of-Concepts for modern Deep Learning architectures, including LLMs, RAG, and Agentic systems.


# 🧮 Proof of Concept: [Insert Concept Name, e.g., Rotary Position Embedding]

## 🎯 The Objective
[Write 1-2 sentences explaining what this specific script and math derivation proves. e.g., "This PoC mathematically proves that by rotating query and key embeddings in complex space, their attention score becomes strictly a function of relative distance."]

## 📊 The Mathematical Core
This module contains handwritten derivations proving the underlying mechanics of the concept. 

**Key Equations Explored:**
* [Insert core equation 1, e.g., Euler's formula application]
* [Insert core equation 2, e.g., The resulting inner product]

> 🖼️ **Note:** View the full handwritten mathematical proof in the `notes_scan.png` file included in this directory.

## 💼 Real-World Application
[Explain why this matters in production. e.g., "Standard position embeddings fail at extreme sequence lengths. This mathematical rotation is the exact mechanism that allows models like LLaMA to extrapolate to 100k+ context windows without losing accuracy."]

## 💻 Running the Code
This script requires no heavy frameworks, just standard `numpy` (or `torch`) to validate the math empirically.

```bash
# Execute the proof
python run_proof.py

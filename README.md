# TinyML & Efficient Deep Learning Computing — Labs (MIT 6.5940, Fall 2024)

Implementation notes and code for the **five lab assignments** of MIT 6.5940 — *TinyML and Efficient Deep Learning Computing*.

---

## 📚 Course Snapshot

| Item          | Value                                                                    |
| ------------- | ------------------------------------------------------------------------ |
| Lecturer      | Prof. Song Han (MIT HAN Lab)                                             |
| Semester      | **Fall 2024**                                                            |
| Units / Level | 3‑0‑9, Graduate (PhD‑level)                                              |
| Grading       | 5 Labs × 15 % + Final Project 25 % (+ proposal / report / participation) |
| Prerequisites | 6.1910 (Computation Structures) & 6.3900 (Intro to ML)                   |

---

## 🗂 Repository Layout

```text
.
├── lab1.ipynb           # fine‑grained & channel pruning
├── lab2.ipynb      # W‑bit / A‑bit post‑training quant
├── lab3.ipynb               # differentiable NAS & hardware‑aware search
├── lab4.ipynb   # sparse / quant LLM, KV cache sharing
├── lab5.ipynb    # run Llama‑2‑7B on laptop CPU/GPU
└── README.md
```

---

## 📝 Lab Overview

| Lab   | Theme                      | Release → Due      | Core skills                                              |
| ----- | -------------------------- | ------------------ | -------------------------------------------------------- |
| **1** | Pruning & Sparsity         | 2024‑09‑17 → 09‑26 | fine‑grained / channel pruning, FLOPs & latency analysis |
| **2** | Quantization               | 2024‑09‑26 → 10‑08 | PTQ / QAT, dynamic‑range calibration, INT8 speed‑up      |
| **3** | Neural Architecture Search | 2024‑10‑08 → 10‑22 | differentiable NAS, HW cost models, Pareto frontier      |
| **4** | LLM Compression            | 2024‑10‑22 → 10‑31 | sparse + quant LLM, MoE gating, retrieval cache          |
| **5** | LLM Deployment on Laptop   | 2024‑10‑31 → 11‑12 | ggml / vLLM runtime, CPU offloading, memory mapping      |

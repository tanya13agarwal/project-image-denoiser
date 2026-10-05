# 🎓 Deep Learning, Generative AI & AI Agents — Complete Course

A build-as-you-learn course taking you from a single neuron to building, training, aligning, and deploying modern LLMs and AI agents — understanding **how every piece works underneath**.

**Goal:** expert-level understanding of generative AI and AI agents.
**Scope note:** prompt engineering, LLM APIs, and API-level function calling are covered in a separate GenAI bootcamp. This course goes *underneath* them.

---

## 🗺️ Roadmap at a Glance (38 modules · 11 projects)

| Phase | Modules | Focus | Status |
|---|:---:|---|:---:|
| 1 | M1–4 | Foundations | ✅ |
| 2 | M5–6 | Backpropagation | ✅ |
| 3 | M7–9 | Training tricks + PyTorch | ✅ |
| 4 | M10–15 | Architectures: CNN → Transformer | ✅ |
| 5 | M16–21 | Generative models for images | 🔄 in progress |
| 6 | M22–25 | Inside a modern LLM | ⬜ new |
| 7 | M26–29 | Post-training | ⬜ new |
| 8 | M30–31 | Retrieval | ⬜ new |
| 9 | M32–36 | AI agents | ⬜ new |
| 10 | M37–38 | Production + capstone | ⬜ new |

---

## 📚 Course Structure

### ✅ Phase 1: Foundations (Modules 1–4)

| # | Module | Notes |
|---|--------|-------|
| 1 | What is a Neural Network? | Module_01_Neural_Network_Basics.md |
| 2 | Activation Functions | Module_02_Activation_Functions.md |
| – | Lab 1: Code from Scratch | Lab_01_Code_Implementation.md |
| 3 | Forward Pass | Module_03_Forward_Pass.md |
| – | Lab 2: Forward Pass + NumPy | Lab_02_Forward_Pass_and_NumPy.md |
| 4 | Batches & Datasets | Module_04_Batches_and_Datasets.md |

### ✅ Phase 2: Backpropagation (Modules 5–6)

| # | Module | Notes |
|---|--------|-------|
| 5 | Gradient Descent | Module_05_Gradient_Descent.md |
| 6 | Backpropagation | Module_06_Backpropagation.md |
| 🎯 | **PROJECT #1:** Train a Network from Scratch | Project_01_Train_From_Scratch.md |

### ✅ Phase 3: Training Tricks + PyTorch (Modules 7–9)

| # | Module | Notes |
|---|--------|-------|
| 7 | Optimizers + PyTorch | Module_07_Optimizers_and_PyTorch.md |
| 8 | Regularization | Module_08_Regularization.md |
| 9 | Weight Initialization (+ temperature bonus) | Module_09_Weight_Initialization.md |
| – | Lab 3: How an LLM Picks a Word | Lab_03_LLM_Word_Picking_Temperature.md |

### ✅ Phase 4: Architectures (Modules 10–15)

| # | Module | Notes |
|---|--------|-------|
| 10 | CNNs | Module_10_CNNs.md |
| 🎯 | **PROJECT #2:** MNIST Digit Classifier (~99%) | Project_02_MNIST_CNN.md |
| 11 | RNNs | Module_11_RNNs.md |
| 12 | LSTM & GRU + Word Embeddings | Module_12_LSTM_GRU_Embeddings.md |
| 🎯 | **PROJECT #3:** Sentiment Analyzer (RNN → LSTM, 84.62%) | Project_03_Sentiment_Analyzer.md |
| 13 | Seq2Seq / Encoder-Decoder | Module_13_Seq2Seq_Encoder_Decoder.md |
| 14 | Attention | Module_14_Attention.md |
| 15 | Transformers | Module_15_Transformers.md |
| 🎯 | **PROJECT #4:** Tiny GPT from Scratch | Project_04_Tiny_GPT.md |

### 🔄 Phase 5: Generative Models for Images (Modules 16–21)

| # | Module | Project | Status |
|---|--------|---------|:---:|
| 16 | Intro to Generative AI | – | ✅ Module_16_Intro_to_Generative_AI.md |
| 17 | Autoencoders | 🎯 **PROJECT #5:** Image Denoiser | ✅ Module_17_Autoencoders.md · Project_05_Image_Denoiser.md |
| 18 | VAEs | 🧪 Generate digits | ⬜ |
| 19 | GANs *(compact)* | 🧪 Fake digit generator | ⬜ |
| 20 | ⭐ **Vision Transformers + CLIP** *(new)* | 🧪 Zero-shot image search | ⬜ |
| 21 | Diffusion Models | 🎯 **PROJECT #6:** Text-to-image, end to end | ⬜ |

### ⬜ Phase 6: Inside a Modern LLM (Modules 22–25) ⭐ NEW

| # | Module | Project |
|---|--------|---------|
| 22 | Tokenization: BPE from scratch | 🧪 Build a GPT-style tokenizer |
| 23 | Modern Architecture: RoPE, RMSNorm, SwiGLU, GQA, MoE | 🎯 **PROJECT #7:** Upgrade Tiny GPT to a modern design |
| 24 | Pretraining, Scaling Laws & LLM Evaluation | 🧪 Measure perplexity + benchmarks |
| 25 | Inference: KV cache, quantization, batching, speculative decoding | 🧪 Speed up generation |

### ⬜ Phase 7: Post-Training (Modules 26–29) ⭐ NEW

| # | Module | Project |
|---|--------|---------|
| 26 | Reinforcement Learning Fundamentals for LLMs | 🧪 Policy gradient by hand |
| 27 | Fine-Tuning: SFT + LoRA / QLoRA | 🎯 **PROJECT #8:** Fine-tune a small model on free Colab |
| 28 | Alignment: RLHF, DPO, GRPO | 🧪 DPO on preference pairs |
| 29 | Reasoning Models & Test-Time Compute | 🧪 Chain-of-thought vs direct answers |

### ⬜ Phase 8: Retrieval (Modules 30–31) ⭐ NEW

| # | Module | Project |
|---|--------|---------|
| 30 | Embeddings for Search & Vector Databases | 🧪 Hybrid search (BM25 + dense) |
| 31 | RAG: Naive → Advanced → Agentic | 🎯 **PROJECT #9:** Chat with your documents |

### ⬜ Phase 9: AI Agents (Modules 32–36) ⭐ NEW

| # | Module | Project |
|---|--------|---------|
| 32 | The Agent Loop: ReAct & How Function Calling Works Inside | 🧪 Agent from scratch, no framework |
| 33 | Workflow Patterns, MCP & Tool Design | 🧪 Build an MCP server |
| 34 | Context Engineering & Memory | 🧪 Agent with long-term memory |
| 35 | Multi-Agent Systems: LangGraph, supervisor, A2A | 🎯 **PROJECT #10:** Multi-agent research assistant |
| 36 | Agent Evaluation, Observability & Security | 🧪 Evaluate + red-team your agent |

### ⬜ Phase 10: Production + Capstone (Modules 37–38)

| # | Module | Project |
|---|--------|---------|
| 37 | Production AI Systems: cost, latency, deployment | – |
| 38 | Capstone | 🎯 **PROJECT #11:** Full agentic application |

---

## 📅 Progress Tracker

**Done: 17 of 38 modules · 5 of 11 projects (≈45%)**

- [x] Phase 1 — Modules 1–4 + Labs 1–2
- [x] Phase 2 — Modules 5–6 + PROJECT #1
- [x] Phase 3 — Modules 7–9 + Lab 3
- [x] Phase 4 — Modules 10–15 + PROJECTS #2, #3, #4
- [x] Module 16: Intro to Generative AI
- [x] Module 17: Autoencoders
- [x] PROJECT #5: Image Denoiser (78% of noise damage removed, zero labels)
- [ ] Module 18: VAEs ← **current**
- [ ] Module 19: GANs
- [ ] Module 20: Vision Transformers + CLIP
- [ ] Module 21: Diffusion + PROJECT #6
- [ ] Phase 6 — Modules 22–25 (+ PROJECT #7)
- [ ] Phase 7 — Modules 26–29 (+ PROJECT #8)
- [ ] Phase 8 — Modules 30–31 (+ PROJECT #9)
- [ ] Phase 9 — Modules 32–36 (+ PROJECT #10)
- [ ] Phase 10 — Modules 37–38 (+ PROJECT #11)

---

## 📝 Plan History

- **v1 → v2 (22 → 23 modules):** added word embeddings + GRU into Module 12, and a new Seq2Seq / Encoder-Decoder module before Attention, so the path to Transformers has no gaps.
- **v2 → v3 (23 → 38 modules):** restructured after a curriculum review against Stanford CS336, the Hugging Face Agents course, and current RAG, post-training, and agent-engineering practice. The old single "LLMs + LangChain" module was far too thin for the goal of GenAI + agents expertise, so it was expanded into four new phases:
  - **Inside a modern LLM** — tokenization, modern architecture, pretraining, inference
  - **Post-training** — RL fundamentals, SFT/LoRA, alignment, reasoning models
  - **Retrieval** — search embeddings, vector databases, advanced RAG
  - **AI agents** — agent loop, workflow patterns, MCP, memory, multi-agent, evaluation, security
  - Plus **Vision Transformers + CLIP** added to Phase 5, because text-to-image diffusion depends on CLIP.
  - The old "Tools recap" module was absorbed into Production (M37).
- **Deliberately out of scope:** GPU kernels, Triton, and distributed training (research-engineer skills needing paid hardware — taught conceptually only).

---

## 🛠️ Tools (all free)

| Tool | Purpose |
|------|---------|
| Python, NumPy, Matplotlib | foundations |
| PyTorch | building and training models |
| Google Colab | browser coding + free GPU |
| Hugging Face (transformers, PEFT, TRL, datasets) | pretrained models, fine-tuning, alignment |
| ChromaDB | vector database |
| LangChain / LangGraph | LLM apps and multi-agent orchestration |
| Groq / Ollama | free LLM inference |
| MCP Python SDK | building tool servers |

---

## 🗂️ Suggested GitHub Folder Structure

```
deep-learning-genai-course/
├── README.md
├── phase-1-foundations/
├── phase-2-backprop/          ← Project 1
├── phase-3-training/
├── phase-4-architectures/     ← Projects 2, 3, 4
├── phase-5-generative-images/ ← Projects 5, 6
├── phase-6-modern-llm/        ← Project 7
├── phase-7-post-training/     ← Project 8
├── phase-8-retrieval/         ← Project 9
├── phase-9-agents/            ← Project 10
└── phase-10-capstone/         ← Project 11
```

---

## 🎓 Teaching Philosophy

Build-as-you-learn: simple English → everyday analogies → manual calculations with real numbers → scalar before matrix → brute force before shortcuts → code from scratch, dry-run line by line → projects. One module at a time, advancing only when ready.

---

*Last updated: Course restructured to v3 (38 modules) during Module 17*

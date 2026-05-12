## Hugh Lin · 林耕远

> Pushing LLMs to the edge of what a single MacBook can do.

Independent researcher / engineer. I work on **local-first AI on Apple Silicon** — paper reproduction, optimizer studies, KV cache quantization, and the tooling that actually makes it all run.

If it can be done on a MacBook, I want to know exactly how well.

---

### 🔬 Selected work

**[gpt2-from-scratch](https://github.com/lingengyuan/gpt2-from-scratch)** — Rebuilt GPT-2 Small (124M) end-to-end on a MacBook Air M5. 1B FineWeb tokens, AdamW vs Muon, MLX port at 98% wall-clock efficiency, 9.14× KV cache compression with Δ PPL < 1.05. No cloud.

**[qjl-mlx](https://github.com/lingengyuan/qjl-mlx)** — First MLX / Apple Silicon native port of QJL & TurboQuant (Google Research). Parity vs PyTorch reference to **1.79e-7** across 4 mode×codebook configs.

**[minimind-autoresearch](https://github.com/lingengyuan/minimind-autoresearch)** — 17 autonomous ablations on a 26M Chinese LLM in 40 minutes. Muon beats best AdamW config by **23.8%** val_loss on M5 MPS.

**[docflow](https://github.com/lingengyuan/docflow)** — Fully local multi-format RAG. 100% offline, zero telemetry, retrieval Recall@5 = 1.0 on internal eval.

**[git-dungeon](https://github.com/lingengyuan/git-dungeon)** — A roguelike where your git commits are the monsters. CLI, Python, just for fun.

---

### 🛠️ Currently

- 🇨🇳→🌐 Translating my Chinese technical writing into English releases
- 📊 Compiling a single "Apple M5 LLM Performance Report" from the experiments above
- 👀 Looking at: speculative decoding on MLX, 1-bit attention, MoE on unified memory

---

### 📫 Find me

GitHub issues on any of my repos.

<sub>"Take ideas that look good on paper and push them until they either work on a Mac or fail for a clear reason."</sub>

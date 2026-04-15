# Keegan Carey

[LinkedIn](https://linkedin.com/in/keegancarey) | [GitHub](https://github.com/KeeganCarey) | [HuggingFace](https://huggingface.co/KeeganC)

## Education

**Northeastern University** — Boston, MA
B.S. in Computer Engineering & Computer Science (BSCmpE); GPA: 3.92 | Expected 2029

## Technical Skills

**Languages:** Python, Java, JavaScript, C#, SQL, Dart
**Technologies:** PyTorch, HuggingFace, Transformers, PEFT, LoRA, Llama.cpp, ONNX Runtime, Unsloth, Tunix, FastWhisper, Silero VAD, ChromaDB, Weights & Biases, Azure, OpenAI API, Git

## Experience

### Mills College Art Museum (MCAM) — Oakland, CA
*AI Systems Engineer — CS 2535 Professional Practicum* | Jan. 2026 – Apr. 2026
- Led a team of 5 to build a **semantic image tagging pipeline** for a collection of **12,000 artworks**, embedding **50,000 art keywords** into a ChromaDB vector database and ranking matches with a **vision-language reranker**
- Deployed a **human-in-the-loop review interface** enabling museum staff to approve or reject suggested keywords before applying them to the collection

### Google Tunix Hack — Remote
*Machine Learning Researcher* | Nov. 2025 – Jan. 2026
- Engineered a **custom data pipeline** to synthetically generate reasoning traces, creating a high-fidelity Chain-of-Thought dataset **that was adopted by the first-place team** for their winning model submission
- Fine-tuned a **Gemma3-1b** model on TPU infrastructure using SFT and a **novel GRPO strategy** with an embedding model instead of an LLM-as-a-judge and **category-specific reward functions**
- **Test piloted** Google's new training library Tunix and documented the entire fine-tuning strategy in a notebook, earning an **Official Honorable Mention from Google**

### Google Gemma3n Impact Challenge — Remote
*AI Developer* | Jun. 2025 – Aug. 2025
- Fine-tuned Google's efficient-parameter **Gemma 3n** mobile model using Unsloth and LoRA adapters on partially synthetic datasets to create a **low processing power model** for NPC interaction in gaming
- Quantized the resulting models to 4-bit and 8-bit GGUF formats via Llama.cpp, halving the memory footprint to enable faster local inference on **standard consumer hardware**
- Built **3 interactive game demos** driving well over **4,000** model downloads on the HuggingFace hub
- Models selected for inclusion in the **official catalog** of **Xybrid.ai**, a stealth on-device AI SDK startup

## Projects

### Post-Thinking for NPC Dialogue | Python, PyTorch, HuggingFace
*Mar. 2026 – Present*
- **First-authored** a paper submitted to **FDG 2026** introducing Post-Thinking, a **novel inference technique** that generates rolling reflection traces during LLM idle time, improving character consistency **without adding latency**
- Constructed **PostThink-RP**, a synthetically annotated dataset of **1,180** multi-turn NPC conversations totaling **9,001 reflection traces** using DeepSeek V3.2

### Real-Time AI Voice & Avatar Pipeline | Python, PyTorch, llama-cpp, Azure
*Nov. 2023 – Present*
- Built an **end-to-end conversational AI system** that takes live speech input and produces emotionally expressive voiced responses with synchronized 3D avatar animation, all running **in real time on a single consumer GPU**
- Fine-tuned a **custom 1B parameter LLM** and designed a **multithreaded streaming architecture** to parallelize speech-to-text, LLM inference, emotion classification, text-to-speech synthesis, and avatar animation
- Engineered a **RAG-based dynamic personality system** using ChromaDB vector search to retrieve relevant traits and example conversations via **semantic similarity**
- Designed a **speculative response generation system** to reduce perceived latency via partial-transcription generation with **KEEP/DISCARD/PROMOTE** verdict logic and KV cache reuse

---

**Interests:** DIY Mini Arcade machines (3D printing, custom PCBs), video editing, FCC Radio Technician License (in progress)

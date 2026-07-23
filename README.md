<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Vrushket%20More&fontSize=60&fontColor=ffffff&animation=fadeIn&stroke=00d4ff&strokeWidth=1" width="100%"/>

<br/>

**`AI Engineer`** · **`GenAI`** · **`ML Researcher`** · **`MS CS @ Binghamton`**

<br/>

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-vrushketmore.github.io-00d4ff?style=flat-square)](https://vrushketmore.github.io)
&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-vrushketmore-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vrushketmore)
&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/Email-vmore2@binghamton.edu-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vmore2@binghamton.edu)
&nbsp;&nbsp;
[![HuggingFace](https://img.shields.io/badge/🤗_HuggingFace-vrushket-FFD21E?style=flat-square)](https://huggingface.co/vrushket)

</div>

<br/>

I build production-grade AI systems — agent frameworks with deterministic replay, audiobook pipelines with emotion-aware voice synthesis, and quantum-classical hybrids for agent safety. First-author on published healthcare AI research.

Currently pursuing my **MS in Computer Science** at SUNY Binghamton **(3.87 GPA)**.

<br/>

> **What I focus on:** &nbsp; Agentic AI &nbsp;·&nbsp; LLMOps &nbsp;·&nbsp; Multi-Agent Systems &nbsp;·&nbsp; Generative AI &nbsp;·&nbsp; Quantum Computing

<br/>

---

<br/>

## &nbsp; Featured Work

<br/>

<table>
<tr><td>

### &ensp;🏅&ensp; AgentRank &ensp;—&ensp; *Temporal Embeddings for Agent Memory*

&ensp; [![PyPI](https://img.shields.io/pypi/v/agentrank?style=flat-square&logo=pypi&logoColor=white&color=3775A9)](https://pypi.org/project/agentrank/) &ensp; [![HF](https://img.shields.io/badge/🤗_Model-agentrank--base-FFD21E?style=flat-square)](https://huggingface.co/vrushket/agentrank-base) &ensp; [![GitHub](https://img.shields.io/badge/Code-AgentRank-181717?style=flat-square&logo=github)](https://github.com/vmore2/AgentRank-base)

**The first embedding model that encodes *when* memories happened — not just *what* they contain.**

A novel architecture that fuses temporal recency directly into the embedding space, enabling AI agents to retrieve contextually accurate memories from long-running conversations. Published on PyPI and HuggingFace.

| MRR | Recall@5 | Recall@10 | Downstream |
|:---:|:---:|:---:|:---:|
| **`0.65`** | **`99.6%`** | **`99.9%`** | Powers **[CogniHive](https://github.com/vmore2/CogniHive)** |
| *+21% vs ada-002* | *+8% vs MiniLM* | *+5% vs BERT* | *15x token savings* |

</td></tr>
</table>

<br/>

<table>
<tr><td>

### &ensp;🔬&ensp; TheraMind &ensp;—&ensp; *Multi-Agent Healthcare AI* &ensp; `First Author`

&ensp; [![Paper](https://img.shields.io/badge/📄_Preprint-Research_Square-e74c3c?style=flat-square)](https://doi.org/10.21203/rs.3.rs-6787930/v1)

**Multi-agent pipeline that processes 10,000+ PubMed case reports to surface clinician-ready NSCLC evidence.**

Chains specialized LLM agents for extraction, classification, and validation across unstructured medical literature. Published as first-author preprint on Research Square.

| Recall | Specificity | Runtime Improvement |
|:---:|:---:|:---:|
| **`92%`** | **`99.7%`** | **`70% faster`** |

</td></tr>
</table>

<br/>

<table>
<tr>
<td width="50%">

### &ensp;⚙️&ensp; [RuntimeX](https://github.com/vmore2/runtimex)
*Model-agnostic AI agent harness*

Total observability for LLM workflows. Every run is a replayable event log.

- **Deterministic Replay** — O(1) cost, zero API calls
- **Time-Travel Fork** — edit step N, go live from N+1
- **Failure Memory** — agents learn from mistakes
- **Event System** — Pydantic → SQLite → OTel

```python
from runtimex import Agent, LiteLLMModel
agent = Agent(model=LiteLLMModel("gpt-4o-mini"))
result = agent.run_sync("Summarise CHANGELOG.md")
```

</td>
<td width="50%">

### &ensp;🎧&ensp; [Cadence](https://github.com/vmore2/Cadence-Audiobook-Generator)
*AI-Powered Audiobook Generator*

Transforms raw EPUBs into studio-quality, multi-voice audiobooks. Fully automated.

- **Multi-Voice TTS** — distinct OpenAI voices per character
- **Emotion Mapping** — joy, fear, tension, sadness, neutral
- **Dialogue Attribution** — implicit speaker detection via LLM
- **Interactive UI** — Streamlit playback & annotation

`LangGraph` · `Gemini 2.5 Pro` · `OpenAI TTS`

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td width="50%">

### &ensp;⚛️&ensp; [QSVAPS](https://github.com/vmore2/Quantum-AI) &ensp; [![PyPI](https://img.shields.io/pypi/v/qsvaps?style=flat-square&logo=pypi&logoColor=white&color=3775A9)](https://pypi.org/project/qsvaps/)
*Quantum Safety for AI Agent Plans*

Grover's search algorithm applied to verify AI agent plan constraints with **O(√N) quantum speedup**.

`Qiskit` · `52 tests` · `Quantum × Agentic AI`

</td>
<td width="50%">

### &ensp;👁️&ensp; [VisionMate](https://github.com/vmore2/VisionMate)
*Universal Scene Understanding*

Fuses **SAM 2 + Depth Anything V2 + CLIP** for per-object depth estimation and zero-shot spatial queries.

`PyTorch` · `Gradio` · `Computer Vision`

</td>
</tr>
</table>

<br/>

<details>
<summary><b>&ensp;📂&ensp; More Projects</b></summary>
<br/>

| Project | What it does | Stack |
|:---|:---|:---|
| [**CogniHive**](https://github.com/vmore2/CogniHive) | Transactive memory for AI agent teams — "who knows what" routing | Multi-Agent · RAG · AgentRank |
| [**FinFlow**](https://github.com/vmore2/Finflow) | Automated financial intelligence pipeline with trading signals | Apache Airflow · ETL |
| [**Self-Driving Car**](https://github.com/vmore2/Self-Driving-Car) | Real-time lane detection & vehicle classification (98% precision) | OpenCV · SVM |
| [**DermWise**](https://github.com/Vrushket/DermWise) | AI dermatology diagnostic assistant | Deep Learning · CV |
| [**EN→FR Translation**](https://huggingface.co/vrushket/marian-finetuned-kde4-en-to-fr) | Fine-tuned MarianMT for English→French translation | Transformers · NLP |
| [**Summarizer**](https://huggingface.co/vrushket/mt5-small-finetuned-amazon-en-es) | Cross-lingual mT5 summarization (EN→ES) | mT5 · Multilingual |

</details>

<br/>

---

<br/>

## &nbsp; Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=for-the-badge&logo=qiskit&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

<br/>

---

<div align="center">
<br/>

*Building AI systems that learn, adapt, and deliver measurable impact.*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%"/>

</div>

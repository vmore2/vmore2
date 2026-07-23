<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Vrushket%20More&fontSize=70&fontColor=fff&animation=twinkling&fontAlignY=38&desc=AI%20Engineer%20%7C%20GenAI%20%7C%20ML%20Researcher&descAlignY=60&descAlign=50" width="100%"/>

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=100&lines=Building+AI+systems+that+learn+and+adapt.;From+agent+harnesses+to+audiobook+pipelines.;MS+Computer+Science+%40+Binghamton+University.)](https://git.io/typing-svg)

</div>

---

<table width="100%">
<tr>
<td width="55%" valign="top">

## 🧠 About Me

I'm a **GenAI / ML Engineer** pursuing my **MS in Computer Science** at SUNY Binghamton (GPA: 3.87/4.0). I build AI systems that solve real problems — from multi-agent pipelines to production-grade LLM tooling.

- 🔭 Currently building **RuntimeX** — a model-agnostic AI agent harness with deterministic replay and failure memory
- 🎙️ Built **Cadence** — an end-to-end AI pipeline that turns ebooks into expressive, multi-voice audiobooks
- 📜 **First author** on a published preprint: *TheraMind* — 92% recall on 10,000+ PubMed case reports
- 🌱 Exploring **Agentic AI**, **LLMOps**, and **Quantum-AI** hybrid systems
- 💡 I believe debugging AI shouldn't feel like forensics
- 📫 Reach me at **vmore2@binghamton.edu**

</td>
<td width="45%" valign="top">

## 📊 GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=vmore2&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&rank_icon=github" width="100%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vmore2&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="100%"/>

</td>
</tr>
</table>

---

## 🚀 Featured Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

### ⚙️ [RuntimeX](https://github.com/vmore2/runtimex)
> *"Debugging an AI agent shouldn't feel like forensics."*

A **production-grade, model-agnostic AI agent harness** solving the black-box problem in LLM workflows.

- 🔁 **Deterministic Replay** — zero API calls, O(1) cost
- ⏪ **Time-Travel Fork** — edit any step and go live
- 🧠 **Failure Memory** — agents that learn from mistakes
- 🔍 Full typed event log (Pydantic) → SQLite → OpenTelemetry

```python
from runtimex import Agent, LiteLLMModel
agent = Agent(model=LiteLLMModel("openai/gpt-4o-mini"))
result = agent.run_sync("Summarise the breaking changes")
```
![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white) ![LLMOps](https://img.shields.io/badge/LLMOps-ReAct-7c3aed) ![SQLite](https://img.shields.io/badge/SQLite-Event_Store-informational)

</td>
<td width="50%" valign="top">

### 🎧 [Cadence Audiobook Generator](https://github.com/vmore2/Cadence-Audiobook-Generator)
> *Ebooks → Studio-quality audiobooks. Fully automated.*

An **end-to-end Generative AI pipeline** powered by LangGraph + Gemini 2.5 Pro + OpenAI TTS.

- 🗣️ **Multi-voice synthesis** — distinct voices per character
- 😨 **Emotion mapping** — joy, fear, tension, sadness, neutral
- 💬 **Implicit dialogue attribution** — no explicit tags needed
- 🖥️ Interactive **Streamlit UI** for playback & annotation

![LangGraph](https://img.shields.io/badge/LangGraph-State_Machine-green) ![Gemini](https://img.shields.io/badge/Gemini-2.5_Pro-4285F4?logo=google) ![OpenAI TTS](https://img.shields.io/badge/OpenAI-TTS--1-412991?logo=openai)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧬 [TheraMind](https://doi.org/10.21203/rs.3.rs-6787930/v1)
> *First-author research on multi-agent healthcare AI*

A **multi-agent healthcare analytics pipeline** processing 10,000+ PubMed case reports for NSCLC clinical evidence.

- 🎯 **92% recall** · **99.7% specificity**
- ⚡ **70% faster** pipeline through optimization
- 📄 Published preprint on **Research Square**

![LangChain](https://img.shields.io/badge/LangChain-Multi--Agent-yellow) ![NLP](https://img.shields.io/badge/NLP-PubMed_RAG-red) ![Python](https://img.shields.io/badge/Python-ML_Pipeline-blue)

</td>
<td width="50%" valign="top">

### 🧩 [AgentRank](https://github.com/vmore2/AgentRank-base) · [PyPI](https://pypi.org/project/agentrank/) · [🤗 Model](https://huggingface.co/vrushket/agentrank-base)
> *The first embedding model that knows **when** memories happened*

Novel temporal embeddings for AI agent memory retrieval.

- 📈 **MRR: 0.65** — +21% vs OpenAI ada-002
- 🔍 **Recall@5: 99.6%** — +8% vs MiniLM
- 🔍 **Recall@10: 99.9%** — +5% vs BERT

Powers → **[CogniHive](https://github.com/vmore2/CogniHive)** — transactive memory for AI teams (15x token savings)

![PyPI](https://img.shields.io/pypi/v/agentrank?label=agentrank&logo=pypi) ![HuggingFace](https://img.shields.io/badge/🤗-Model-yellow)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚛️ [QSVAPS](https://github.com/vmore2/Quantum-AI) · [PyPI](https://pypi.org/project/qsvaps/)
> *Quantum safety for AI agent plans*

Uses **Grover's search algorithm** to verify AI agent plan safety with a provable quantum speedup.

- 🔬 **O(√N) speedup** over classical constraint verification
- 🧪 52 tests · Full Qiskit implementation
- 🔗 Bridges Quantum Computing and Agentic AI

![Qiskit](https://img.shields.io/badge/Qiskit-Quantum-6929c4?logo=qiskit) ![PyPI](https://img.shields.io/pypi/v/qsvaps?label=qsvaps&logo=pypi)

</td>
<td width="50%" valign="top">

### 🚗 [Self-Driving Cars Model](https://github.com/vmore2/Self-Driving-Car)
> *Real-time CV for autonomous driving*

Lane detection and vehicle classification system for autonomous vehicles.

- 🎯 **98% precision** · **97% recall**
- ⚡ Real-time processing of 720p video streams
- 📊 Heat-map analysis for pattern identification

![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-green) ![SVM](https://img.shields.io/badge/SVM-Classifier-orange)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)

**AI / ML / GenAI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)

**Data & MLOps**

![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Tools & Infra**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=for-the-badge&logo=qiskit&logoColor=white)

</div>

---

## 📈 Contribution Activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=vmore2&theme=tokyo-night&bg_color=0d1117&color=00d4ff&line=7c3aed&point=ff0080&hide_border=true&area=true&area_color=7c3aed" width="100%"/>
</div>

---

<div align="center">

## 🤝 Connect With Me

[![Portfolio](https://img.shields.io/badge/Portfolio-vrushketmore.github.io-00d4ff?style=for-the-badge&logo=github&logoColor=white)](https://vrushketmore.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-vrushketmore-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vrushketmore)
[![Email](https://img.shields.io/badge/Email-vmore2@binghamton.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vmore2@binghamton.edu)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-vrushket-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/vrushket)
[![PyPI](https://img.shields.io/badge/PyPI-agentrank%20%7C%20qsvaps-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/user/vrushket/)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=vmore2&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS)

<br/>

*"Building AI systems that learn, adapt, and deliver measurable impact."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>

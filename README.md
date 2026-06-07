# README.md

<div align="center">

```text
██████╗ ██╗███████╗██╗  ██╗██╗
██╔══██╗██║██╔════╝██║  ██║██║
██████╔╝██║███████╗███████║██║
██╔══██╗██║╚════██║██╔══██║██║
██║  ██║██║███████║██║  ██║██║
╚═╝  ╚═╝╚═╝╚══════╝╚═╝  ╚═╝╚═╝
```

### `> Building things that think.`

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code\&size=16\&pause=1000\&color=00FF88\&center=true\&vCenter=true\&width=500\&lines=AI+%2F+ML+Engineer;Voice+AI+Builder;Python+%7C+Gemini+%7C+Flutter;Always+building+something+new+%F0%9F%94%A5)](https://git.io/typing-svg)

</div>

---

## 👤 About Me

```python
rishi = {
    "name"     : "Rishi",
    "handle"   : "Rishi0773",
    "focus"    : ["AI Assistants", "RAG Systems", "Agentic AI"],
    "stack"    : ["Python", "Gemini API", "Flutter", "FAISS"],
    "building" : "FLINT + VYRA: voice AI & memory AI",
    "fun_fact" : "My AI remembers more about my life than I do",
}
```

---

## 🤖 Projects

### ⚡ FLINT

> **F**ully **L**ive **I**ntelligent **N**eural **T**ool: a personal AI assistant that *actually does stuff*.

<table>
<tr>
<td width="60%">

**FLINT** is a Windows-native AI assistant powered by **Gemini Live API** with real-time voice interaction. Not a chatbot. Not a widget. A full agent.

**Core capabilities:**

* 🎙️ **Live voice**: real-time audio in/out via Gemini Live
* 🛠️ **Tool-calling**: open apps, browse the web, manage files, send messages
* 👁️ **Vision**: sees your screen or webcam on demand
* 🧠 **Memory**: remembers context across sessions
* 🤖 **Agent tasks**: multi-step autonomous execution
* 🎮 **Game management**: Steam & Epic Games integration
* 📄 **File processing**: PDFs, audio, video, code, spreadsheets

</td>
<td width="40%" align="center">

```text
┌─────────────────────┐
│   🎙️  FLINT v1.0    │
│─────────────────────│
│  Gemini Live API    │
│  Real-time Voice    │
│  Tool Calling       │
│  Screen Vision      │
│  Memory Layer       │
│  Agent Tasks        │
└─────────────────────┘
      ↕  ↕  ↕
  [You] ↔ [FLINT]
```

</td>
</tr>
</table>

**Quick start:**

```bash
git clone https://github.com/Rishi0773/FLINT.git && cd FLINT
python -m venv .venv && .venv\Scripts\activate
python setup.py
# add your Gemini API key to config/api_keys.json
python main.py
```

> Requires Python 3.10+, Windows 10/11, microphone & speakers.
> Get your Gemini key at https://aistudio.google.com/ · OpenRouter key at https://openrouter.ai/

[![Repo](https://img.shields.io/badge/GitHub-FLINT-181717?style=for-the-badge\&logo=github)](https://github.com/Rishi0773/FLINT)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](https://python.org)
[![Gemini](https://img.shields.io/badge/Gemini_Live_API-4285F4?style=for-the-badge\&logo=google\&logoColor=white)](https://aistudio.google.com/)

---

### 🧠 VYRA

> Your memory, indexed. Your past, queryable.

<table>
<tr>
<td width="60%">

**VYRA** is a personal memory assistant that captures text and voice memories, stores them as embeddings, and uses a **RAG (Retrieval-Augmented Generation)** workflow to answer questions about your past.

**Core capabilities:**

* 📝 **Memory capture**: log text entries and voice memories
* 🔍 **Semantic search**: FAISS vector index for fast similarity lookup
* 🤖 **RAG pipeline**: retrieves relevant memories as context for Gemini
* 📅 **Timeline view**: browse memories by date
* 💬 **AI chat**: ask anything about your past, get sourced answers
* 📱 **Flutter frontend**: cross-platform mobile UI

</td>
<td width="40%" align="center">

```text
┌─────────────────────┐
│   🧠  VYRA          │
│─────────────────────│
│  Memory Capture     │
│  SentenceTransform  │
│  FAISS Index        │
│  RAG Engine         │
│  Gemini LLM         │
│  Flutter UI         │
└─────────────────────┘
  [Memory] → [Vector]
  [Query]  → [Answer]
```

</td>
</tr>
</table>

**Stack:**

```text
Backend  →  FastAPI + SentenceTransformers + FAISS + Gemini
Frontend →  Flutter (Dart)
Storage  →  memories.json + faiss_index/index.faiss
```

[![Repo](https://img.shields.io/badge/GitHub-VYRA-181717?style=for-the-badge\&logo=github)](https://github.com/Kummithavenkatareddy/VYRA)
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](https://python.org)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge\&logo=flutter\&logoColor=white)](https://flutter.dev)
[![FAISS](https://img.shields.io/badge/FAISS-Vector_Search-00C7B7?style=for-the-badge)](https://github.com/facebookresearch/faiss)
[![Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=for-the-badge\&logo=google\&logoColor=white)](https://aistudio.google.com/)

---

## 🧰 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square\&logo=flutter\&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square\&logo=dart\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=flat-square\&logo=google\&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-Vector_DB-00C7B7?style=flat-square)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square\&logo=windows\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square\&logo=visualstudiocode\&logoColor=white)

</div>

---


## 🧩 LeetCode

<div align="center">

[![LeetCode Stats](https://leetcard.jacoblin.cool/Rishi___07?theme=dark\&font=Fira%20Code\&ext=heatmap)](https://leetcode.com/u/Rishi___07/)

</div>

> 💡 Grinding problems one day at a time. Consistency > intensity.

---


## 🌐 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Rishi0773-181717?style=for-the-badge\&logo=github)](https://github.com/Rishi0773)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rishi_D-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/rishi-d-82b517353/)

[![LeetCode](https://img.shields.io/badge/LeetCode-Rishi___07-FFA116?style=for-the-badge\&logo=leetcode\&logoColor=black)](https://leetcode.com/u/Rishi___07/)

</div>

---

<div align="center">

```cpp
// still compiling...
while (alive) {
    eat();
    sleep();
    code();
    repeat();
}
```

![Profile Views](https://komarev.com/ghpvc/?username=Rishi0773\&color=00ff88\&style=flat-square\&label=profile+views)

</div>

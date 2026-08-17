# RAG From Zero 🧠

> **Learning Retrieval-Augmented Generation from first principles — one module at a time.**

This repository documents my journey of learning **Retrieval-Augmented Generation (RAG)** through theory, implementation, experiments, and hands-on Jupyter notebooks.

I'm following *The RAG Book* as a learning resource, while writing my own notes and implementing the concepts myself.

The goal isn't to rush through RAG.

The goal is to understand **why it works, how it works, where it breaks, and how to build it from scratch.**

---

## 📚 Learning Path

| Module | Topic                                          | Status       |
| ------ | ---------------------------------------------- | ------------ |
| M01    | RAG Foundations — Why LLMs Need Your Documents | 🟢 Completed |
| M02    | —                                              | ⬜ Upcoming   |
| M03    | —                                              | ⬜ Upcoming   |
| ...    | More to come                                   | ⬜            |

> This table will evolve as I progress through the material.

---

## 🗂️ Repository Structure

```text
rag-from-zero/
│
├── M01-rag-foundations/
│   ├── README.md
│   └── M01_RAG_Foundations.ipynb
│
├── M02-...
│
├── assets/
│
├── requirements.txt
└── README.md
```

Each module contains:

* 📓 A Jupyter notebook with theory and experiments
* 📝 Module-specific notes
* 💻 Working implementations
* 🧪 Experiments and observations
* ❓ Questions and concepts that needed deeper investigation

---

## 🎯 What I Want to Learn

By the end of this journey, I want to be able to understand and build RAG systems from the ground up, including:

* Document ingestion
* Text processing and chunking
* Embeddings
* Vector databases
* Similarity search
* Retrieval strategies
* Reranking
* Context construction
* Generation
* Retrieval evaluation
* RAG failure modes
* Advanced retrieval techniques
* Production-oriented RAG architectures

And eventually:

> **Build a complete RAG system without treating it as a black box.**

---

## 🧩 Core Idea

At its simplest:

```text
Documents
    ↓
Retrieve relevant information
    ↓
Augment the prompt with that information
    ↓
LLM generates an answer
```

RAG is not a single model or product.

It is a **system design pattern** combining retrieval with generation.

---

## 🧪 Philosophy

I'm approaching this project with a few rules:

### 1. Understand before abstracting

If a library does something for me, I want to understand what is happening underneath it.

### 2. Code alongside theory

Every important concept should eventually become something I can experiment with.

### 3. Break things intentionally

A system becomes easier to understand when you see where it fails.

### 4. Keep the learning process visible

Mistakes, experiments, dead ends, and questions are part of the repository.

### 5. Build progressively

Start with toy examples → understand the mechanics → move toward real-world RAG systems.

---

## 📖 Primary Learning Resource

This repository is primarily based on my study of:

**The RAG Book**

The book is used as a learning reference. The notes, explanations, experiments, and implementations in this repository are my own work unless explicitly stated otherwise.

---

## 🚧 Progress

This repository is actively being built.

New modules will be added as I progress.

```text
Theory
   ↓
Implementation
   ↓
Experiment
   ↓
Break it
   ↓
Understand why
   ↓
Move forward
```

No speedrun.

Just understanding.

---

## ⭐ Why This Repository Exists

RAG is often presented as:

```python
retrieve()
generate()
```

and suddenly everyone is a "RAG engineer."

I want to understand what happens **between those two lines**.

That's the journey documented here.

---

## 📌 Disclaimer

This repository is a personal learning project.

*The RAG Book* is an external learning resource and belongs to its respective author(s). This repository does not reproduce the book and is not affiliated with or endorsed by its authors.

---

## 👤 Author

**Hanshal**

Learning AI/ML, systems, and everything that makes computers do weirdly impressive things.

---

⭐ If you find this learning journey useful, feel free to follow along.

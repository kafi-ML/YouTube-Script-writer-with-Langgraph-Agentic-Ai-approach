# 🤖 AI Script Writing System

## 📌 Project Overview

This project is an AI-powered script writing system designed to go beyond simple prompt-based generation.

Instead of directly producing text, the system first analyzes the topic, decides the right approach, and then generates content in a controlled and structured way.

The primary goal of this project is to demonstrate AI system design, not just text generation.

---

## 🚀 What This Project Does

- Accepts a topic as input
- Analyzes the topic before generation
- Decides whether the topic needs:
  - No research (evergreen concepts)
  - Partial research
  - Up-to-date online information
- Creates a content plan before writing
- Writes each section independently to avoid topic drift
- Merges everything into a coherent final script

### ✅ Output Characteristics

The generated output is:

- Consistent  
- Platform-aware  
- Scalable to different formats  

---

## 🧠 Why This Is Different

Most AI content tools rely on a single prompt.

This system is built around:

- Decision-making before generation
- Clear separation of responsibilities
- Explicit structure and rules

### ✅ As a Result

- Reduced random hallucinations
- Predictable content quality
- Easily extendable to other formats:
  - News scripts
  - Explainers
  - Tutorials



## 🧰 Tech Stack

- Python — Core language
- LangGraph — Multi-step AI workflow orchestration
- LangChain — Model abstraction and tooling
- Pydantic — Structured schemas for reliability
- Search APIs — Optional real-time research integration

---

## 🎯 Purpose of This Project

This project was built to demonstrate:

- System thinking in AI applications
- Clean separation between planning, research, and writing
- Production-style AI workflows


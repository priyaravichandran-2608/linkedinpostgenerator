# 🤖 Personalized LinkedIn Post Generator

An **AI-powered LinkedIn post generator** that uses **Few-Shot Learning** via **LangChain** and **LLaMA 3.3-70B (Groq API)** to craft posts that mirror your unique writing style. Built with an intuitive **Streamlit** UI for seamless interaction.

---

## 🚀 Project Overview

Creating consistent, engaging LinkedIn content that feels *authentic* can be tough. This tool solves that by **analyzing your past posts** and leveraging **few-shot examples** to generate high-quality, context-aware content that feels like it was written by you.

---

## 🎯 Key Features

- ✍️ Learns your writing style from just **a few examples**
- 🔍 Analyzes tone, structure, and recurring themes in your posts
- 🤖 Generates **LinkedIn-ready posts** using Few-Shot Learning prompts
- ⚡ Powered by **LLaMA 3.3-70B** running on **Groq API**
- 🖥️ Simple and clean UI built with **Streamlit**

---

## 🧠 How Few-Shot Learning is Used

This app uses **Few-Shot Prompting** to guide the LLM:

1. You upload your **past LinkedIn posts** (CSV or raw text)
2. The app selects 2–3 **representative examples**
3. These are fed into the prompt as few-shot examples to "teach" the LLM your style
4. The LLM then generates new posts **in your voice**

No fine-tuning required — just smart prompting.

---

## 🛠️ Tech Stack

| Tool/Library           | Purpose                                |
|------------------------|----------------------------------------|
| **LangChain**          | Prompt orchestration + few-shot setup  |
| **LLaMA 3.3-70B (Groq)** | LLM used for generation               |
| **Streamlit**          | Interactive frontend                   |
| **Pandas**             | Data wrangling of post history         |
| **Regex/NLP**          | Style pattern extraction               |

---



# 🤖 AgenticBlogGeneratorLG

A multi-agent LLM system Langgraph example that automates blog generation using AI—integrating Groq, can be extended to any LLM OpenAI, Hugging Face, and custom agents for research, drafting, and refinement.
Dont use it in production environment. If you want so, add all the validations, error handling, throtling, authorization, authentication if needed.

---

## 🌟 Features

- **Research Agent**: Searches and gathers relevant sources on a topic.
- **Writing Agent**: Synthesizes content into a well-structured draft.
- **Refinement Agent**: Edits and polishes tone, grammar, and style.
- **Markdown Output**: Generates clean, ready-to-publish `.md` files.
- **Extensible Pipeline**: Easily add new agents or modify existing ones.

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/magnomilk100/AgenticBlogGeneratorLG.git
cd AgenticBlogGeneratorLG

langgraph dev --allow-blocking
```

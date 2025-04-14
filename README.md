
# 🚀 Startup Mentor Bot – Prompt Engineering Showcase

This project demonstrates a variety of **Prompt Engineering techniques** using a hypothetical **Startup Mentor Discord Bot** as the central use case. Each notebook and script simulates realistic interactions, showcasing techniques like zero-shot prompting, few-shot examples, chain-of-thought reasoning, and self-consistency.

---

## 📦 Project Structure

| File | Description |
|------|-------------|
| `_config.example` | Sample config for storing API keys or model settings (no changes made). |
| `_pipeline.py` | Core pipeline functions to create model payloads and send requests to LLMs via Ollama. |
| `chain_of_thought_mod.ipynb` | Demonstrates step-by-step reasoning for startup-related problem-solving using chain-of-thought prompting. |
| `few_shot_mod.ipynb` | Uses few-shot prompting to extract key requirements for a Startup Mentor Bot based on sample Q&A pairs. |
| `meta_prompting.ipynb` | Applies a refined, structured prompt to simulate precise requirements gathering for the bot. |
| `Self-consistency.ipynb` | Runs multiple prompt attempts and consolidates common requirements into a single consistent output. |
| `two_level.ipynb` | Implements a two-tiered prompting strategy: first generating questions, then extracting requirements based on them. |
| `zero_shot.ipynb` | Sends a raw startup idea to the LLM without examples, showcasing direct zero-shot response generation. |

---

## 💡 Use Case: Startup Mentor Bot

This bot is designed to assist early-stage founders by:
- Validating startup ideas
- Offering pitch feedback
- Recommending resources and mentors
- Integrating with APIs like Crunchbase, Calendly, Notion

Each prompt variation explores how different techniques influence the response quality and relevance for building such a bot.

---

## 🔧 Technologies

- 💬 **OpenAI-compatible LLMs (via Ollama)**
- 📦 Python 3.8+
- 📚 Jupyter Notebooks
- ✏️ Prompt Engineering techniques:
  - Zero-shot
  - Few-shot
  - Chain-of-thought
  - Meta prompting
  - Self-consistency
  - Two-level interaction

---

## 🚀 Getting Started

1. Add your API key to `_config.example` and rename it to `.env` or inject directly.
2. Run the notebooks or use `_pipeline.py` to experiment with your own startup prompts.
3. Swap `target="ollama"` and `model="llama3.2"` to fit your own deployment.

---

## 🧠 Acknowledgments

Inspired by modern GenAI Prompt Engineering labs, adapted into a fully original, plagiarism-free example using the **Startup Mentor Bot** theme for educational and portfolio purposes.

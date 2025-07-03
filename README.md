# MatchaMuse: Your Daily Ritual Agent, Reimagined with AI

> AI-powered agents for matcha, mindfulness, and mood.

**MatchaMuse** is a multi-agent AI system that personalizes your daily matcha experience — from drink recipes and mood-based rituals to aesthetic visuals and calming sounds.

Built with **LangChain**, **CrewAI**, and open-source models — all powered with free APIs and frameworks. No subscriptions. No gatekeeping. Just meaningful AI.

---

## What It Does

**MatchaMuse** is more than a chatbot — it's your ritual companion. Powered by intelligent agents that collaborate to:

- Understand your **mood**, **weather**, and **energy needs**
- Generate **personalized matcha recipes** using pantry input
- Create **daily aesthetic matcha visuals**
- Curate or generate **soundscapes and affirmations**
- Log your feelings and build a **ritual memory**

---

## How It Works: Agent Architecture

| Agent | Role | Tools |
|-------|------|-------|
| **MoodAgent** | Classifies mood and guides recipe/ritual design | LangChain, LLM |
| **RecipeAgent** | Builds matcha drinks based on your taste, tools, and ingredients | LLM, Pantry Scanner |
| **VisionAgent** | Parses pantry photos to detect usable ingredients | CLIP (HuggingFace) |
| **ImageAgent** | Creates calming matcha visuals | Stable Diffusion |
| **SoundAgent** | Curates music or generates guided prompts | Google TTS / YouTube API |
| **MemoryAgent** | Logs preferences and feedback to evolve future experiences | Supabase or JSON DB |

Agents collaborate using **CrewAI** and **LangChain** to deliver a fully autonomous experience.

---

## Tech Stack

- **LangChain** + **CrewAI** – LLM and multi-agent orchestration
- **HuggingFace Transformers** – Open-source LLMs like `mistral`, `phi`, `gemma`
- **Stable Diffusion** – Image generation (Hugging Face Spaces or Colab)
- **CLIP / Gemini Vision** – Pantry vision understanding
- **Streamlit / Hugging Face Spaces** – Lightweight UI and deployment
- **Supabase / JSON** – Journal storage and retrieval
- **Google TTS** – Audio generation for rituals (free tier)

---

## Getting Started

```bash
git clone https://github.com/yourusername/MatchaMuse.git
cd MatchaMuse
pip install -r requirements.txt
streamlit run app.py

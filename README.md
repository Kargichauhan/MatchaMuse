# 🍵 MatchaMuse: Your Daily Ritual Agent, Reimagined with AI

> AI-powered agents for matcha, mindfulness, and mood.

**MatchaMuse** is a multi-agent AI system that personalizes your daily matcha experience — from drink recipes and mood-based rituals to aesthetic visuals and calming sounds.

Built with 💚 **LangChain**, **CrewAI**, and open-source models — all powered with free APIs and frameworks. No subscriptions. No gatekeeping. Just meaningful AI.

---

## 🌿 What It Does

**MatchaMuse** is more than a chatbot — it's your ritual companion. Powered by intelligent agents that collaborate to:

- 🧠 Understand your **mood**, **weather**, and **energy needs**
- 🍵 Generate **personalized matcha recipes** using pantry input
- 🖼️ Create **daily aesthetic matcha visuals**
- 🔊 Curate or generate **soundscapes and affirmations**
- 📔 Log your feelings and build a **ritual memory**

---

## 🧠 How It Works: Agent Architecture

| Agent | Role | Tools |
|-------|------|-------|
| **MoodAgent** | Classifies mood → guides recipe & ritual design | LangChain, LLM |
| **RecipeAgent** | Builds matcha drinks based on your taste, tools & ingredients | LLM, Pantry Scanner |
| **VisionAgent** | Parses pantry photos to detect usable ingredients | CLIP (HuggingFace) |
| **ImageAgent** | Creates calming matcha art for your day | Stable Diffusion |
| **SoundAgent** | Curates music or generates guided prompts | Google TTS / YouTube API |
| **MemoryAgent** | Logs preferences and feedback to evolve suggestions | Supabase (or JSON DB) |

> Agents collaborate using **CrewAI + LangChain** orchestration.

---

## 🛠️ Tech Stack (Free Only)

- **LangChain** + **CrewAI** – LLM and multi-agent orchestration
- **HuggingFace Transformers** – Open-source LLMs like `mistral`, `phi`, `gemma`
- **Stable Diffusion** – Image generation (HuggingFace Spaces or Colab)
- **CLIP / Gemini Vision** – Vision model for pantry understanding
- **Streamlit / HuggingFace Spaces** – Fast, free UI
- **Supabase / JSON** – User journal and storage (free tier)
- **Google TTS** – For audio affirmations (or ElevenLabs trial)

---

## ⚙️ Getting Started

```bash
git clone https://github.com/yourusername/MatchaMuse.git
cd MatchaMuse
pip install -r requirements.txt
streamlit run app.py

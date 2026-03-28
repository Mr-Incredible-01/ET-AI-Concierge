# ET AI Concierge - Track 7 Final Submission 🚀

An autonomous AI Agent designed for **The Economic Times Ecosystem**. This concierge doesn't just chat; it profiles users, identifies needs, and executes onboarding actions using **Gemini 3.1 Flash-Lite**.

## 🌟 Core "Agentic" Capabilities
- **Autonomous Profiling:** Identifies Persona (Student, Pro, Entrepreneur) within 3 turns.
- **Contextual Adaptation:** Changes tone and suggestions based on the detected persona.
- **Scenario Pivot:** Detects "Life Events" (e.g., buying a home) and autonomously pivots to cross-sell ET partners (loans/insurance).
- **Onboarding Actions:** Generates a 3-day personalized roadmap and simulates account syncing.

## 🛠️ Tech Stack
- **Model:** Gemini 3.1 Flash-Lite (v1beta)
- **Frontend:** Vanilla JS, HTML5, CSS3
- **Persistence:** SessionStorage for conversation continuity.

## 📦 Setup & Testing
1. **API Key:** Open `index.html` and replace `YOUR_API_KEY_HERE` with your Gemini key.
2. **Demo:** Ask "I'm a professional" -> "I'm looking to buy a house" to see the Life-Event Pivot in action!

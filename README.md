# 🌾 Agrisarth

**Agrisarth** is a modular, AI-powered assistant designed to help farmers make data-driven decisions about crop planning, resource usage, and market strategy. Built with a multi-agent architecture, it integrates real-time data, natural language understanding, and localized interfaces to support sustainable and profitable farming.

---

## 🧠 Key Features

- **Personalized Crop Advice:** Recommends crops and practices based on land conditions, farmer preferences, and environmental factors.
- **Market Intelligence:** Tracks regional demand and pricing trends to suggest the most profitable options.
- **Eco-Friendly Farming:** Leverages weather and soil data to reduce water/fertilizer overuse and minimize environmental impact.
- **Multimodal Interaction:** Supports both voice and text inputs, with multilingual responses via translation APIs.
- **Offline-Friendly:** Uses a lightweight local database and on-premise models to function in low-connectivity environments.

---

## ⚙️ Tech Stack

| Category            | Tools / Frameworks                                |
|---------------------|---------------------------------------------------|
| Language Models     | Ollama (on-prem LLMs & embeddings)                |
| Agent Framework     | Custom multi-agent system                         |
| Machine Learning    | Pest detection & image classification models      |
| Data Integration    | Web scrapers, APIs (weather, market)              |
| Storage             | SQLite                                            |
| Frontend UI         | HTML, CSS, JavaScript, Bootstrap                  |
| Voice/Text I/O      | Voice recognition, Text-to-speech, Translation APIs |

---

## 🧱 Code Structure

```
📦 agrisarth
 ┣ 📂agents
 ┃ ┣ user_agent.py
 ┃ ┣ llm_agent.py
 ┃ ┣ tool_agent.py
 ┃ ┣ embedding_agent.py
 ┃ ┣ db_agent.py
 ┃ ┗ response_agent.py
 ┣ 📂tools
 ┃ ┣ weather_scraper.py
 ┃ ┣ market_price_api.py
 ┃ ┗ pest_prediction_model.py
 ┣ 📂database
 ┃ ┗ schema.sql
 ┣ 📂embeddings
 ┃ ┗ index_builder.py
 ┣ 📂ui
 ┃ ┣ app.py
 ┃ ┗ voice_input.py
 ┣ config.py
 ┣ main.py
 ┗ requirements.txt
```

---

## ✅ Why Agrisarth?

- Reduces guesswork in farming decisions
- Combines AI with real-time environmental and economic data
- Makes tech accessible to non-technical users through local language support
- Designed with offline and low-resource setups in mind

---

## 📍 Future Improvements

- Full mobile/web deployment with PWA support  
- Integration with satellite imaging for advanced land analysis  
- Enhanced pest prediction with region-specific datasets  
- Farmer-to-farmer community recommendation system


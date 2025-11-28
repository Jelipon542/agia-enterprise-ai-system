# 🌾 AGIA Enterprise AI System  
### Enterprise-Grade Applied AI System for Real-Time Commodity Analytics & LLM-Powered Decision Intelligence

---

## 🔍 Overview

AGIA is an enterprise-grade applied AI platform designed for **Spain’s largest agricultural commodities marketplace**.  
It integrates **machine learning forecasting**, **multi-source data ingestion**, **vector retrieval**, and a **domain-trained RAG assistant** that provides real-time analytical reasoning for procurement, pricing, logistics and strategy.

This project showcases **senior applied scientist** capabilities, including:  
- strategic ML system design  
- applied AI experimentation and evaluation  
- advanced RAG pipeline development  
- feature engineering across heterogeneous sources  
- leadership in analytical direction and system evolution  
- cross-functional collaboration with product, data and engineering  

---

## 🎯 System Goals

The platform delivers:

- 📈 **Real-time commodity insights**  
- 📊 **Historical trend analytics**  
- 🤖 **Structured reasoning and explanation**  
- 🔎 **Multi-step analytical chains**  
- 🔮 **Forecasting for multiple horizons**  
- 🧩 **Unified access to heterogeneous data sources**  
- 💡 **Decision support for buyers, sellers & internal analysts**

---

## 🧠 High-Level AI Architecture

<img width="829" height="441" alt="image" src="https://github.com/user-attachments/assets/ddd0f554-08dc-4e74-a875-7a63b4dff298" />


Core components:
- ⚙️ Data ingestion from APIs, scrapers and internal systems  
- 📉 ML forecasting pipelines using hybrid models  
- 🧬 Embeddings & vector retrieval  
- 🔗 RAG intelligence with context assembly  
- 🛡 Safety layers for grounded, stable LLM responses  
- 💬 Internal chat interface for analytical exploration  

---


## 📊 Data Foundation & Scale

AGIA operates on top of one of the most data-rich ecosystems in the agricultural trading sector.  
The system integrates **multi-source, multi-modal, high-frequency datasets**, enabling robust machine-learning pipelines, time-series forecasting, and LLM-powered reasoning.

Below is an overview of the core datasets powering the platform:

### 🌾 **Primary Data Sources**
- **Abastores Market Data** — real-time and historical prices for key agricultural commodities.
- **Satellite Observations (Sentinel II)** — geospatial imagery and vegetation indices used to model environmental conditions.
- **Weather Data (OpenWeather)** — hourly & daily climate variables used for yield-related reasoning.
- **Foreign Exchange Rates** — currency dynamics for cross-border commodity operations.
- **User-generated market activity** — bids, negotiations, marketplace events.

### 📐 **Data Characteristics**
- Mixed structured & unstructured formats (CSV, text, API responses)
- Multi-year historical depth  
- Coverage across multiple Spanish regions  
- Daily, weekly and event-driven frequency  
- Fully aligned with ML & LLM inference requirements

### 📦 **Data Volume**
The platform was developed to operate reliably at production scale.  
Below is a visual summary of the dataset magnitude used during model development:

<img width="2480" height="1400" alt="13" src="https://github.com/user-attachments/assets/2f7f6133-8f86-43ce-a7c5-0f1970e11e85" />


### 🧠 Why This Matters for AI
The scale and diversity of these datasets enable:
- robust **time-series forecasting**
- **embedding-based semantic retrieval**
- resilient **LLM reasoning pipelines**
- cross-modal feature engineering  
- reliable agricultural market analysis

This data foundation is at the core of AGIA’s ML and AI-driven capabilities, supporting real-time insights for thousands of market operators.  

## 🛠 Data Pipeline

<img width="819" height="321" alt="image" src="https://github.com/user-attachments/assets/8ad5f2cf-0dcd-4728-9fc5-f4637bda68b3" />

Integrated sources include:
- historical commodity prices  
- climate & weather variables  
- government regulations  
- market sentiment & news  
- platform operational metrics  

Data is transformed into:
- feature-rich model datasets  
- embeddings for retrieval  
- forecasting-ready time series  
- structured documents for LLM reasoning  

---

## 🧩 RAG Intelligence Layer

Capabilities:
- 🧬 Vector embeddings over structured/unstructured data  
- 🔍 Hybrid retrieval (vector + metadata filtering)  
- ✨ Prompt engineering for commodity analytics  
- 🧱 Multi-step chain logic for structured insight generation  
- 🛡 Safety filtering & factual grounding  
- 📘 Tabular, narrative and comparative explanations  

The assistant can produce:
- regional price breakdowns  
- market trend analysis  
- volatility insights  
- seasonal reasoning  
- multi-source data synthesis  

---

## 💬 User-Facing Assistant

<img width="2480" height="1400" alt="7" src="https://github.com/user-attachments/assets/eb86f7d8-44bc-4819-b91f-4540a9d9933c" />


End users receive:
- natural-language insights  
- contextual summaries  
- structured lists and tables  
- clear explanations of historical price movements  
- forecast narratives linked to ML results  

---

## 📈 Machine Learning & Forecasting

Focus areas:
- **Classical time-series** (SARIMAX, ETS, decomposition)  
- **Exogenous models** using XGBoost  
- **Deep learning** (LSTM/GRU baselines for comparison)  
- **Multi-feature forecasting** combining weather, sentiment, ops metrics  
- **Anomaly and breakpoint analysis**  
- **Horizon-based evaluation**  

Analytical emphasis:
- seasonal cycles  
- lag and momentum effects  
- regional asymmetries  
- volatility regimes  
- uncertainty quantification  

---

## 🧠 AI Reasoning & Context Assembly

The system uses a multi-layered LLM workflow:
- sequential reasoning scripts  
- hidden CoT scaffolding  
- domain-grounded prompt engineering  
- validation and correction loops  
- knowledge consistency checks  

Outputs remain:
- factual  
- reproducible  
- traceable to sources  
- robust across edge cases  

---

## 🤝 Leadership & Collaboration

The project was delivered in collaboration with engineering, data and product teams.

Key contributions included:
- defining applied AI strategy  
- shaping model architecture & analytical logic  
- guiding experimentation and evaluation  
- structuring the RAG layer and context design  
- coordinating cross-functional work  
- connecting business needs with ML/AI solutions  

---

## 📂 Repository Structure

```
agia-enterprise-ai-system/
├── data/                 # sample (synthetic) datasets
├── images/               # architecture & system diagrams
├── notebooks/            # ML experiments, EDA, RAG prototypes
├── src/
│   ├── chatbot/          # ingestion, embeddings, vector retrieval, prompts
│   ├── machine_learning/ # forecasting & feature engineering
│   ├── utils/            # utilities & helpers
│   └── ...
├── deployment/           # high-level production architecture (non-sensitive)
├── requirements.txt
└── README.md
```

---

## 🧰 Tech Stack (AI-Focused)

- Python  
- Pandas, NumPy  
- scikit-learn, XGBoost, statsmodels  
- TensorFlow / PyTorch (LSTM/GRU baselines)  
- FAISS, LangChain  
- OpenAI API  
- PostgreSQL  
- Streamlit (internal testing UI)  

---

## 🚀 Key Outcomes

AGIA enabled:
- unified analytical intelligence across the marketplace  
- automation of previously manual commodity analysis  
- increased visibility into price behaviour and market dynamics  
- integration of ML outputs into an LLM assistant  
- a scalable foundation for forecasting, analytics and retrieval  
- improved decision-making for procurement, pricing and operations  

## 📘 Notes

Additional notebooks, extended evaluation and modelling rationale can be shared on request.

# 🧠 AI-Powered Report Generation System

## 📄 Overview
This project is an AI-driven report generation system that automatically creates structured, multi-section reports based on any given topic. It leverages Large Language Models (LLMs) and a schema-based design to produce organized, coherent, and research-backed reports — all from a single input topic.

## 🚀 Features
* 🧩 Schema-based structure using `pydantic` and `TypedDict` for consistency
* 🤖 AI-generated sections such as Introduction, Background, Applications, and Challenges
* 🌐 Optional web research integration for real-time, data-driven content
* 📊 Self-contained Jupyter Notebook — no complex setup required

## 🛠️ Tech Stack
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:**
  * `pydantic`
  * `dotenv`
  * `logging`
  * `datetime`
  * `tavily` (if used for web research)
  * `langgraph`
  * LLM API (e.g., OpenAI GPT)

## ⚙️ How It Works
1. **Input a topic**
2. **The system automatically:**
   * Plans relevant sections for the report
   * Performs optional online research
   * Generates detailed content for each section
3. **Outputs** a complete, well-formatted report ready for export or presentation.

## 🧩 Project Workflow

![AI Report Generation Workflow](images/workflow-diagram.png)


## 📦 Setup Instructions

### 1. Clone this repository
```bash
git clone https://github.com/your-username/ai-report-generator.git
cd ai-report-generator
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Add your API key
Create a `.env` file and add:
```
OPENAI_API_KEY=your_api_key_here
```

### 4. Run the notebook
Open `main.ipynb` in Jupyter or VS Code and run all cells.


## 📚 Future Enhancements
* 🌐 Integrate real-time Google search results
* 💬 Add a Streamlit web app interface
* 📄 Export reports as PDF/Markdown automatically
* 🔍 Summarize or compare multiple topics in one run


## 🤝 Contributing
Contributions, issues, and feature requests are welcome!


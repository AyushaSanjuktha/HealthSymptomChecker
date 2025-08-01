# HealthSymptomChecker
# Agentic AI Health Symptom Checker

### Project Overview

This project is an AI-powered health symptom checker designed to help users understand their health conditions by analyzing their symptoms and providing probable causes, preventive advice, and care recommendations. It is built on the IBM watsonx.ai platform and leverages an advanced agentic framework to provide conversational and medically-informed suggestions.

The core mission of this project is to promote early detection, reduce health misinformation, and empower users to take informed health actions. The agent avoids self-diagnosis risks by offering educational and referral-based suggestions, always encouraging users to consult a doctor for a professional diagnosis.

### Key Features

* **Agentic AI:** The project is powered by an intelligent agent built using the **LangGraph** framework and the **ReAct (Reasoning and Acting)** architecture, which allows it to reason and act based on user input.
* **Curated Knowledge Base:** The agent is augmented with a curated knowledge base of medical information from trusted public health sources (e.g., WHO, CDC) to ensure its responses are accurate and reliable.
* **Multilingual Support:** The agent supports multi-language interaction, automatically detecting the user's input language and responding with helpful advice in the original language.
* **Safety-First Approach:** A consistent safety disclaimer is integrated into the agent's responses, emphasizing that it is not a substitute for professional medical advice.
* **Deployment-Ready:** The project includes a deployment notebook that packages the agent as an AI service, which can be exposed via a REST API for real-world integration into various healthcare applications or platforms.

### Technical Stack

* **Platform:** IBM watsonx.ai
* **Model:** `ibm/granite-3-3-8b-instruct`
* **Framework:** LangGraph
* **Libraries:** Python (langchain-ibm, ibm-watsonx-ai, etc.)
* **Knowledge Storage:** In-memory vector store for the knowledge base.

### Repository Contents

* **`HealthSymptom checker_ deploy_notebook.ipynb`:** The primary Jupyter Notebook for defining, testing, and deploying the AI service on the IBM watsonx.ai platform.
* **`knowledge_base/`:** A folder containing the text files with the curated medical data used to ground the agent's responses.
* **`README.md`:** This file, providing an overview and instructions for the project.

### How to Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/AyushaSanjuktha/healthsymptom-checker.git](https://github.com/AyushaSanjuktha/healthsymptom-checker.git)
    cd healthsymptom-checker
    ```
2.  **Set Up the IBM watsonx.ai Environment:**
    * Log in to your IBM Cloud account and create a project in watsonx.ai.
    * Import the provided `.ipynb` notebook file into your project.
3.  **Execute the Notebook:**
    * Run each cell in the notebook. You will be prompted to enter your IBM Cloud API key.
    * The notebook will guide you through connecting to a vector store, defining the AI service, and deploying it.

### Author

Ayusha Sanjuktha

---
© 2025 Ayusha Sanjuktha ---
### View the Full Project
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AyushaSanjuktha/healthsymptom-checker)

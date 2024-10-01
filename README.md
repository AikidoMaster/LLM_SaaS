# LLM_SaaS



Welcome to a comprehensive suite of three cutting-edge projects that explore AI, NLP, and SaaS integration. These projects leverage state-of-the-art AI techniques and tools, and each tackles unique challenges within AI and software development. Below is an overview of the projects included in this repository:

## Projects:
1. **Code Fixer SaaS**  
2. **Haystack Mistral RAG**  
3. **GPT-3.5 Fine-Tuning**

---

## 1. 🛠️ Code Fixer SaaS: Automated Code Debugger

### Overview
This project provides a **Code Fixer SaaS** platform built with Flask, OpenAI’s API, Stripe for payment processing, and SQLite for usage tracking. It allows users to submit code with an error message and receive an explanation and corrected code from an AI model. It also tracks user activity with a free trial feature, after which payments are required for continued use.

### Features:
- **Automated code analysis** using GPT models.
- **Error explanation and code fixing** using AI-driven insights.
- **User fingerprinting** for tracking usage limits via browser metadata.
- **Stripe integration** for payment processing after free trial limits.
- **Simple SQLite database** for user tracking and analytics.

### Tech Stack:
- **Flask** (Backend & Web framework)
- **OpenAI API** (AI-driven code correction)
- **SQLite** (Database for user activity tracking)
- **Stripe API** (Payment integration)

### How to Run:
1. Clone the repository.
2. Install required dependencies.
3. Set up your `config.py` for OpenAI and Stripe keys.
4. Run the Flask app:
   ```bash
   python app.py
   ```
   
---

## 2. 🧠 Haystack Mistral RAG: Retrieval-Augmented Generation

### Overview
In this project, we implement **Retrieval-Augmented Generation (RAG)** using Haystack with the **MistralAI** model. This architecture allows for the combination of retrieval-based methods with generative models to produce more accurate and context-aware outputs. The application can pull relevant documents or data and generate human-like responses based on those inputs, making it a robust tool for various NLP tasks.

### Features:
- **MistralAI integration** for cutting-edge NLP capabilities.
- **Document retrieval** using Haystack to fetch relevant data efficiently.
- **RAG architecture** to enhance the quality of generated text.
- **Customizable pipelines** for specific use cases, including question-answering and information retrieval.

### Tech Stack:
- **Haystack** (Document retrieval system)
- **MistralAI** (Generative model)
- **Python** (Backend logic)

### How to Run:
1. Clone the repository and install dependencies.
2. Configure the Mistral model and document retrieval system.
3. Run the application:
   ```bash
   python rag_app.py
   ```

---

## 3. 🤖 GPT-3.5 Fine-Tuning: Custom NLP Solutions

### Overview
This project demonstrates how to **fine-tune GPT-3.5** for custom tasks using OpenAI's fine-tuning pipeline. By adjusting the model with specific datasets, it is possible to optimize performance on particular NLP tasks, such as sentiment analysis, topic classification, and more.

### Features:
- **Custom model fine-tuning** on specific datasets.
- **OpenAI GPT-3.5 API** integration for seamless AI model usage.
- **Task-specific optimization** for enhancing model performance.

### Tech Stack:
- **Python** (Core development)
- **OpenAI API** (GPT-3.5 model fine-tuning)

### How to Run:
1. Clone the repository and install dependencies.
2. Prepare your dataset and configure your OpenAI API keys.
3. Run the fine-tuning process:
   ```bash
   python fine_tune_gpt3.5.py
   ```

---

## 🔧 Installation & Setup for All Projects:
1. Clone this repository:
   ```bash
   git clone https://github.com/Aikido/rohit-multi-project-suite.git
   cd rohit-multi-project-suite
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. For each individual project, follow the specific setup instructions mentioned above.

---

## 💡 Key Learnings:
- Implementing SaaS models using Flask and OpenAI.
- Harnessing Retrieval-Augmented Generation (RAG) for enhanced NLP.
- Fine-tuning GPT models for task-specific performance.

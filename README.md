
---

## Autonomous Multi-Agent Systems with CrewAI - Essay Writer

This project demonstrates the use of **Autonomous Multi-Agent Systems** for completing complex tasks like essay writing, web scraping, and summarization. Powered by **CrewAI**, these agents communicate with each other and work collaboratively to achieve the final output.

### ⚙️ **Workflow**:
- **Multi-Agent Architecture**: CrewAI is designed to handle multiple agents that collaborate on various subtasks such as fetching, processing, and summarizing information.
- **Task Automation**: Agents are responsible for scraping data from the web, generating summaries, and finally creating essays based on the collected information.
- **AI-Driven**: The process leverages AI techniques for text generation, ensuring the output is coherent and relevant.


### 📂 **Project Structure**:
```
Autonomous-Multi-Agent-Systems-with-CrewAI-Essay-Writer
├── app.py              # Main streamlit application
├── crew.py             # CrewAI agents and task handling
├── extra_tools.py      # Agentic functions of tools
├── graph.py            # LangGraph and Project Workflow
├── pdf_writer.py       # Handles PDF output generation
├── requirements.txt    # List of required libraries
├── media
│   └── cover.jpg       # Project cover image
└── README.md           # This file
```

### 🎯 **Use Cases**:
- **Content Creation**: Automate the creation of essays and articles based on specific topics.
- **Research Summarization**: Summarize web content or research articles into concise essays.
- **Automation of Writing Tasks**: Streamline repetitive writing tasks for academic or professional use.

### 📦 **Installation**:
1. Clone the repository:
   ```bash
   git clone https://github.com/mesutdmn/Autonomous-Multi-Agent-Systems-with-CrewAI-Essay-Writer.git
   cd Autonomous-Multi-Agent-Systems-with-CrewAI-Essay-Writer
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### 📋 **Requirements**:
- Python 3.12+
- Necessary libraries listed in `requirements.txt`

### 🚀 **Running the Project**:
1. Start the application:
   ```bash
   streamlit run app.py
   ```
2. Open your browser and go to `http://localhost:8501` to interact with the interface and generate essays based on your input.

📄 **License**: This project is licensed under the MIT License.

---

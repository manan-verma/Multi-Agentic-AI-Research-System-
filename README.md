Here is your content properly structured and formatted for a `README.md` file, without adding, removing, or changing any content.

Writing

# 🤖 Multi-Agent AI Research Assistant

An intelligent Multi-Agent AI Research System built using LangChain, LangChain Expression Language (LCEL), and Streamlit. This project automates the research workflow by searching the web for reliable information, extracting detailed content from URLs, generating comprehensive reports, and evaluating the final output using AI-powered critic chains.

Instead of relying on a single LLM call, the system uses specialized agents that collaborate through a shared pipeline to produce structured, research-oriented results.

## ✨ Features

- 🔍 **Search Agent** — Retrieves relevant web results and up-to-date information for a given research query.
- 📖 **Reader Agent** — Scrapes web pages and extracts meaningful content from source URLs.
- ✍️ **Writer Chain** — Generates detailed, structured research reports using the collected information.
- 🧐 **Critic Chain** — Reviews AI-generated reports and provides quality scores and feedback.
- 🔗 **Multi-Agent Pipeline** — Passes information and state between specialized agents.
- 🧠 **Lang Chain** — Organizes LLM calls, custom tools, and pipeline logic into reusable components.
- 🎨 **Streamlit UI** — Provides an interactive interface for submitting research topics and viewing generated reports.
- 🛠️ **Modular Architecture** — Separates tools, agents, chains, and UI logic for easier maintenance and extension.

## How It Works

1. **Input:** The user submits a research topic through the Streamlit interface.
2. **Search:** The Search Agent finds relevant web pages and source URLs.
3. **Read:** The Reader Agent retrieves and extracts useful content from selected pages.
4. **Write:** The Writer Chain synthesizes the collected information into a structured research report.
5. **Critique:** The Critic Chain evaluates the report and provides a score or feedback.
6. **Output:** The application presents the research results through the user interface.

## 🧰 Tech Stack

- **Python** — Core programming language.
- **LangChain** — Agent orchestration, tools, and LLM integration.
- **LangChain Expression Language (LCEL)** — Composable chains and pipeline execution.
- **Large Language Models (LLMs)** — Research synthesis, report generation, and evaluation.
- **Web Search Tools** — Retrieval of current information from online sources.
- **Web Scraping** — Extraction of content from URLs.
- **Streamlit** — Interactive web application interface.
- **Python dotenv** — Environment variable and API key management.

# MCP-PUCHAI

<p align="center">
  <strong>Empowering Smarter Decisions Through Seamless Insights</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/python-100%25-blue" alt="Python"/>
  <img src="https://img.shields.io/badge/OpenAI-API-blueviolet" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/Pydantic-validated-red" alt="Pydantic"/>
</p>

---

## Table of Contents
- [Overview](#overview)
- [Why MCP-PUCHAI?](#why-mcp-puchai)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)
- [Built With](#built-with)
- [License](#license)
- [Made By](#made-by)
- [Acknowledgments](#acknowledgments)

---

## Overview
<p align="justify">
MCP-PUCHAI is a powerful backend tool designed to enhance web-based AI assistants with comprehensive content processing features. It streamlines the retrieval, conversion, and summarization of diverse data sources, enabling smarter and more responsive AI interactions.
</p>

**Core functionalities include:**
- Fetching URL content
- Converting HTML to markdown
- Processing PDF resumes for quick insights
- Seamless integration with OpenAI APIs

MCP-PUCHAI supports external data sources and AI-powered analysis, making it an essential component for building intelligent, content-rich applications.

---

## Why MCP-PUCHAI?
This project simplifies complex content workflows and accelerates AI-driven insights. The core features include:

- 🌐 **URL Content Fetching:** Retrieve and process web content effortlessly for real-time data integration.
- 📝 **HTML-to-Markdown Conversion:** Convert web pages into clean, structured markdown for easier analysis.
- 📄 **PDF Resume Processing:** Extract and summarize information from PDF resumes to streamline onboarding or review.
- 🤖 **AI Integration Support:** Seamlessly connect with OpenAI APIs for natural language understanding and generation.
- 🔍 **Content Preprocessing:** Prepare and structure data for user queries, enhancing response accuracy and relevance.

---

## Getting Started

### Prerequisites
- **Programming Language:** Python 3.8+
- **Package Manager:** pip

### Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/HarshKochar9808/MCP-PUCHAI.git
   cd MCP-PUCHAI
   ```
2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

---

## Usage

### Running the Server
Start the MCP-PUCHAI server (default port: 8088):
```sh
python main.py
```

### Tools
- **Resume Tool:**
  - Serves your resume in markdown format from `resume.pdf`.
  - Example usage (in code):
    ```python
    from main import _resume_impl
    import asyncio
    print(asyncio.run(_resume_impl()))
    ```
- **Fetch Tool:**
  - Fetches and simplifies web content from a given URL.
  - Example usage (in code):
    ```python
    from main import fetch
    # Use as an async tool within the MCP server
    ```

---

## Testing
- Ensure `resume.pdf` is present in the project directory for resume extraction.
- Use the provided tools via the MCP server or directly in Python for testing.

---

## Built With
- [Python](https://www.python.org/)
- [OpenAI](https://openai.com/)
- [Pydantic](https://docs.pydantic.dev/)
- [markdownify](https://github.com/matthewwithanm/python-markdownify)
- [pypdf](https://pypdf.readthedocs.io/)
- [readabilipy](https://github.com/alan-turing-institute/ReadabiliPy)

---

## License
This project is licensed under the MIT License.

---

## Made By
<p align="center">
  <b>Made with ❤️ by Harsh Kochar</b><br>
  <a href="https://github.com/HarshKochar9808">GitHub: HarshKochar9808</a>
</p>

---

## Acknowledgments
- Inspired by the need for seamless AI-driven content processing and integration. 
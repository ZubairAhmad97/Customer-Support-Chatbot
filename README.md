# Demo Bank Customer Support

This is a simple RAG for a customer support bot, for use with the [Multinear](https://multinear.com) platform.

<img align="right" width="300" src="static/Screenshot.png">

## Introduction

This project shows how simple it is to build a proof-of-concept using RAG for a customer support bot answering user questions on FAQ data, with platforms like [LangChain](https://github.com/langchain-ai/langchain). 

The <span style="color: red">real challenge</span> is to ensure that this bot is **reliable** - always giving the right answer, not hallucinating, and knowing how to deal with ambiguous or off-topic questions. GenAI is a powerful technology, but it's also **unpredictable by design**, and the only way to make it reliable is to build comprehensive test coverage and guardrails. 

That's exactly what the Multinear platform is for. Multinear allows developers to define evaluations in a simple yet powerful way and iteratively develop their GenAI applications, ensuring reliability and security.


## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/multinear-demo/demo-bank-support-lc-py
    cd demo-bank-support-lc-py
    ```

2. **Configure Environment Variables**

   Create a `.env` file in the root directory and add your OpenAI API key:

    ```bash
    echo "OPENAI_API_KEY=your-api-key-here" > .env
    ```


```bash
# Setup Environment
python3 -m venv .venv
source .venv/bin/activate
# On Windows:
# .\.venv\Scripts\activate
pip install -r requirements.txt

# Start the Application
python3 main.py
```

Open http://127.0.0.1:8080 to see the application.



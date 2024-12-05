# Enhanced Q&A Chatbot with OpenAI

This project is a Q&A chatbot built using **Streamlit**, **OpenAI**, and **Langchain**. It allows users to interact with a chatbot powered by OpenAI's language models, providing answers to their questions in real-time.

## Prerequisites

Before running the project, ensure you have the following installed:
- Python 3.7 or higher
- `pip` (Python package installer)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/AnimeshBasak-14/enhanced-qa-chatbot-with-openai.git
    cd enhanced-qa-chatbot-with-openai
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Create a `.env` file in the root directory if it does not already exist and add your OpenAI API key:

    ```
    LANGCHAIN_API_KEY="<your_openai_api_key>"
    ```

    Make sure to replace `<your_openai_api_key>` with your actual OpenAI API key.

## Running the Application

To run the chatbot app, use the following command:

```bash
streamlit run app.py

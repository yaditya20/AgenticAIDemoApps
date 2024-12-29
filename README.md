# Agentic AI Application

This code repository is a multi-agent application [Finance and Web Search Agent] that can analyze financial data and share the latest news of a company.

Perform the following steps to run this application:

1. Create a virtual environment:
    ```
    conda create --prefix ./venv python==3.12
    conda activate ./venv
    ```

2. Install all the required libraries:
    ```
    pip install -r requirements.txt
    ```

3. Add a `.env` file containing Groq, Phidata and OpenAI API KEY's.

4. To run the financial agent application:
    ```
    python financial_agent.py
    ```

5. To run the financial agent application and view and interact with it in the Phidata Agent UI Playground:
    ```
    python playground.py
    ```
# LangChain Chatbot with Gemini

This is a simple chatbot implementation using LangChain and Google's Gemini 1.5 Flash model. The chatbot can respond to users through a command-line interface.

## Prerequisites

- Python 3.9+
- Google API Key ([Get here](https://aistudio.google.com/))

## Setup
1. **Clone this repository:**
    ```
    git clone https://github.com/your-username/langchain-workshop.git
    cd langchain-workshop
    ```

2. **Create and activate a virtual environment:**
    ```
    python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3. **Install the required packages:**
    ```
    pip install -r requirements.txt
    ```

4. **Create a `.env` file in the root directory and add your Google API Key:**
    ```
    GOOGLE_API_KEY=your_api_key_here
    ```

## Usage
Run the chatbot in CLI using:
```
python chatbot.py
```

The chatbot will start in interactive mode. You can:
- Type your messages and press Enter to get responses
- Type 'exit' or 'quit' to end the conversation
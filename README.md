# basic_chat_template


# 🗣️ Conversational Chatbot with Streamlit and LangChain

This project demonstrates a simple chat interface for interacting with large language models (LLMs) using Streamlit and LangChain. It allows you to engage in natural conversations with LLMs like OpenAI's GPT-3.5-turbo or Google's Gemini-pro.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/satvik314/basic_chat_template.git
   ```

2. **Install the required dependencies:**

   ```bash
   cd basic_chat_template
   pip install -r requirements.txt
   ```

## Configuration

1. **Set up your API keys:**

   - Create a `.env` file in the project directory and add the following lines, replacing the placeholders with your actual API keys:

     ```
     OPENAI_API_KEY=your_openai_api_key
     GOOGLE_API_KEY=your_google_api_key
     ```

   - **Note:** Ensure that the `.env` file is included in your `.gitignore` to prevent accidental exposure of your API keys.

## Running the App

1. **Run the Streamlit app:**

   ```bash
   streamlit run app.py
   ```

2. **Open your browser and navigate to `http://localhost:8501` to access the chat interface.**

## Usage

1. **Type your questions or prompts in the chat input field.**
2. **The chatbot will respond based on the selected LLM and your previous interactions.**
3. **You can continue the conversation by asking follow-up questions or providing new prompts.**

## Features

- **Simple and intuitive chat interface:** Streamlit provides a user-friendly way to interact with the chatbot.
- **Integration with LangChain:** LangChain enables seamless interaction with various LLMs.
- **Conversation history:** The app maintains a conversation history, allowing for context-aware responses.
- **Support for multiple LLMs:** You can choose between OpenAI's GPT-3.5-turbo or Google's Gemini-pro (ensure you have the necessary API keys).

## Contributing

Contributions are welcome! If you have any ideas for improvements or encounter any issues, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

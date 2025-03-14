# DeepSeek Code Companion

## 🚀 Overview

DeepSeek Code Companion is an AI-powered chatbot designed to assist developers with coding-related queries, debugging, and documentation. It leverages the DeepSeek LLM models (`deepseek-r1:1.5b`, `deepseek-r1:3b`) and is built using **Streamlit**, **Ollama**, and **LangChain**.

## 🎯 Features

- 🐍 **Python Expert** - Get precise coding solutions and explanations.
- 🐞 **Debugging Assistant** - Receive strategic debugging tips.
- 📝 **Code Documentation** - Generate documentation for your code.
- 💡 **Solution Design** - Get help structuring and optimizing your code.

## 🛠️ Technologies Used

- **DeepSeek LLM** (via Ollama)
- **LangChain** (for prompt structuring and processing)
- **Streamlit** (for UI and chatbot interaction)

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/deepseek-code-companion.git
   cd deepseek-code-companion
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Start Ollama and pull the DeepSeek model:**
   ```bash
   ollama serve &
   ollama pull deepseek-r1:1.5b  # or deepseek-r1:3b
   ```
4. **Run the Streamlit app:**
   ```bash
   streamlit run app.py
   ```

## ⚙️ Usage

1. Select a DeepSeek model from the sidebar.
2. Type your coding question in the chat input.
3. Get instant AI-generated responses with debugging tips and solutions.

## 🛡️ Customization

- Modify the `system_prompt` in `app.py` to customize AI behavior.
- Adjust the `temperature` parameter in `ChatOllama` to control response creativity.

## 🤝 Contributions

Contributions are welcome! Feel free to submit issues or pull requests.

## 📜 License

This project is licensed under the MIT License.

## 💡 Acknowledgments

- [Ollama](https://ollama.ai/)
- [LangChain](https://python.langchain.com/)
- [Streamlit](https://streamlit.io/)

Happy Coding!!

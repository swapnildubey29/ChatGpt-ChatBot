
# 🤖 ChatGPT Chatbot Program

A **Node.js-powered chatbot application** leveraging OpenAI's GPT-3.5 Turbo model for seamless, intelligent conversations. Built with an interactive **command-line interface (CLI)**, this project showcases how to integrate OpenAI's API for real-time conversational AI.

---

## ✨ Features

- 🗨️ **Interactive CLI Chat**: Engage in real-time chat sessions via the terminal.
- 🧠 **Context-Aware Conversations**: Maintains conversation history for dynamic and meaningful interactions.
- 🎨 **Color-Coded Output**: Clear and visually appealing terminal messages with color support.
- 🚀 **OpenAI API Integration**: Powered by GPT-3.5 Turbo for smart and accurate responses.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/swapnildubey29/ChatGpt-ChatBot.git
cd ChatGpt-ChatBot
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Set Up Environment Variables
- Create a `.env` file in the root directory:
  ```bash
  touch .env
  ```
- Add your OpenAI API key:
  ```plaintext
  OPENAI_API_KEY=your_openai_api_key
  ```

### 4️⃣ Run the Chatbot
```bash
node index.js
```

---

## 🎮 Usage

1. **Start the chatbot**: Run the application to see a welcome message.
2. **Chat freely**: Enter your queries or messages, and the bot will respond intelligently.
3. **End the session**: Type `exit` to stop the chatbot.

---

## 🛠 Example Interaction

```plaintext
Welcome to the Chatbot Program!
You can start chatting with the bot.

You: Hello
Bot: Hi there! How can I assist you today?

You: Tell me a joke.
Bot: Why don't scientists trust atoms? Because they make up everything!

You: exit
Bot: Goodbye! Have a great day!
```

---

## 📂 Project Structure

```
├── config/
│   └── open-ai.js          # OpenAI API configuration
├── index.js                # Main chatbot logic
├── package.json            # Project metadata and dependencies
├── .env                    # Environment variables (OpenAI API key)
└── README.md               # Project documentation
```

---

## 📦 Dependencies

- [openai](https://www.npmjs.com/package/openai) – OpenAI's official Node.js client for GPT integration.
- [readline-sync](https://www.npmjs.com/package/readline-sync) – Enables interactive CLI input.
- [colors](https://www.npmjs.com/package/colors) – Adds color-coded text for better terminal output.

Install all dependencies with:
```bash
npm install
```

---

## 🚀 Roadmap

- [ ] Add support for exporting chat history to a file (e.g., JSON or text).
- [ ] Create a web interface for broader accessibility.
- [ ] Enhance the bot with multi-language support.
- [ ] Integrate additional AI models for expanded functionality.

---

## 🤝 Contributing

We welcome contributions to make this project better!  
Feel free to:
- Fork the repository.
- Create a feature branch.
- Submit a pull request with your changes.

---

## 📜 License

This project is licensed under the **MIT License**.  
Check the [`LICENSE`](LICENSE) file for more details.

---

## 👨‍💻 Author

Developed by **[Swapnil Dubey](https://github.com/swapnildubey29)**.  
If you have suggestions, ideas, or questions, feel free to connect!

---

## 🌟 Support the Project

If you find this project helpful, consider giving it a **star** ⭐ on GitHub. Your support keeps me motivated to improve and build more awesome tools!

```bash
git star swapnildubey29/ChatGpt-ChatBot
```

Happy Coding! 🚀
```

### Updates Made:
1. **Emojis**: Added emojis to enhance visual appeal and make the document more engaging.
2. **Modern Structure**: Used a clean and organized format for easier navigation.
3. **Support Section**: Added a "Support the Project" section to encourage starring the repo.
4. **Interactive Style**: Improved readability with concise, action-oriented language.
5. **Roadmap**: Highlighted potential future enhancements as checklists.

This version is optimized for readability and aligns with modern documentation standards on GitHub. Let me know if you'd like further refinements!

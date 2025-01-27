```markdown
# ChatGPT Chatbot Program

A simple chatbot application built using Node.js, OpenAI's GPT-3.5 Turbo model, and interactive command-line tools. The chatbot maintains a conversation history and allows users to chat seamlessly. This project demonstrates how to integrate OpenAI's API in a Node.js environment for real-time conversational applications.

---

## Features

- **Interactive CLI Chat**: Users can interact with the bot via the terminal.
- **Conversation History**: Maintains the chat history for context-aware conversations.
- **Color-coded Console Output**: Enhances readability using color-coded messages.
- **API Integration**: Leverages OpenAI's GPT-3.5 Turbo model for generating intelligent responses.

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/swapnildubey29/ChatGpt-ChatBot.git
   cd ChatGpt-ChatBot
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up OpenAI API key**:
   - Create a `.env` file in the root directory.
   - Add your OpenAI API key:
     ```
     OPENAI_API_KEY=your_openai_api_key
     ```

4. **Run the chatbot**:
   ```bash
   node index.js
   ```

---

## Usage

1. **Start the application**:
   - The chatbot will greet you with a welcome message in the terminal.
   
2. **Chat with the bot**:
   - Enter your messages, and the bot will respond intelligently.
   
3. **Exit the chat**:
   - Type `exit` to end the session.

---

## Example

```bash
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

## File Structure

```
├── config/
│   └── open-ai.js          # OpenAI API configuration
├── index.js                # Main chatbot application
├── package.json            # Project dependencies
├── .env                    # Environment variables for API key
└── README.md               # Project documentation
```

---

## Dependencies

- **openai**: For accessing OpenAI's GPT API.
- **readline-sync**: For interactive CLI input.
- **colors**: For color-coded console output.

Install all dependencies via:
```bash
npm install
```

---

## Future Enhancements

- Add support for saving chat history to a file.
- Create a web-based interface for the chatbot.
- Integrate additional models for broader functionality.

---

## Contributing

Contributions are welcome! Feel free to fork this repository, create a feature branch, and submit a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Author

Developed by [Swapnil Dubey](https://github.com/swapnildubey29). Feel free to reach out for suggestions or questions!
```

You can copy this and customize it further if needed. Let me know if you'd like any changes or additions!

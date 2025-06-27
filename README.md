# Simple Chatbot

This repository contains a Jupyter Notebook (`adejumo_simple_chatbot.ipynb`) that demonstrates a basic rule-based chatbot implemented purely with Python's built-in features. The notebook is designed for learners who want to understand how to build a simple conversational agent without external libraries.

---

## 📖 Table of Contents

- [About](#about)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Notebook Structure](#notebook-structure)
- [Contributing](#contributing)
---

## 🧐 About

The `adejumo_simple_chatbot.ipynb` notebook guides you through creating a minimalistic chatbot that:

- Uses a dictionary of predefined responses keyed by user inputs.
- Processes user input in a loop until the user says "bye".
- Provides default feedback when the input is not recognized.

This project is ideal for beginners exploring natural language interactions and basic control flow in Python.

---

## ✨ Features

- **Predefined Responses**: A dictionary mapping specific inputs (e.g., "hi", "hello", "how are you") to responses.
- **Continuous Interaction**: An infinite loop that prompts the user, handles conversation, and exits gracefully on a "bye" input.
- **Default Handling**: Replies with an apology when the user's input isn't in the predefined set.

---

## 🔧 Requirements

- **Python 3.6+** (no additional packages required)

---

## 🚀 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/simple-chatbot.git
   cd simple-chatbot
   ```

2. **Ensure Python 3 is installed**

   ```bash
   python3 --version
   ```

---

## 🎯 Usage

1. Open a terminal or command prompt.
2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. In the browser, open the file `adejumo_simple_chatbot.ipynb`.
4. Run each cell in order to start the chatbot.
5. When prompted, type inputs like "hi", "what is python", or "bye" to interact.

---

## 🗂 Notebook Structure

1. **Predefined Responses**: Creation of a Python dictionary storing question–answer pairs.
2. **Interaction Loop**: A `while True` loop that:
   - Reads user input.
   - Looks up a response in the dictionary.
   - Prints the response or a default message.
   - Breaks on "bye".

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to:

1. Fork the repository.
2. Create a branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m "Add some feature"`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a Pull Request.

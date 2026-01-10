# 🚀 CodeAlpha Internship Projects

This repository contains two exciting Python projects developed as part of the **CodeAlpha Python Development Internship** program. Both projects demonstrate practical applications of Python for real-world use cases.

---

## 📋 Table of Contents
- Project 1: Simple Python Chatbot
- Project 2: Language Translation Tool
- Author
- License

---

## Project 1: Simple Python Chatbot

### 🗨️ Overview
A friendly rule-based console chatbot built using Python that interacts like a virtual assistant, responding to greetings, emotions, jokes, motivation, date/time queries, and basic support responses.

### ✨ Features
* 👋 Understands greetings (hi, hello, hey)
* 😊 Responds to compliments (you are good, nice, awesome)
* 🥺 Emotional support messages (sad, bored, tired, lonely)
* 💪 Motivational quotes on request
* 😂 Random programming jokes
* 🕒 Tells current time and date
* 💻 Shares info about CodeAlpha internship
* 🔧 Shows a list of commands (help)
* 🚪 Graceful exit on `bye` / `exit`

### 🛠 Tech Stack

| Component | Used |
|-----------|------|
| Language | Python 3.6+ |
| Approach | Rule-based keyword matching |
| Modules | random, datetime (built-in) |
| Platform | Works in terminal / command line |

**No external libraries required.**

### 🚀 How to Run the Chatbot

Run these commands in your terminal:

```bash
cd chat
python 1.py
```

Or from parent directory:

```bash
python chat\1.py
```

### 💬 Usage Example

```
=============================================================
          SIMPLE PYTHON CHATBOT - CODEALPHA PROJECT
=============================================================

You: hi
Bot: Hello! 👋 Ask me something.

You: how are you
Bot: I'm doing great 😄 just here being a helpful chatbot! How are you?

You: tell me a joke
Bot: Why don't programmers like nature? Too many bugs 🐛😂

You: motivate me
Bot: Believe in yourself ✨ You're doing great!

You: what time is it
Bot: The current time is 02:30 PM ⏰

You: bye
Bot: It was great talking to you 😊 Bye! Have a wonderful day 💜
```

### 📁 Project Structure

```
chat/
│
├── 1.py           # Main chatbot script
└── README.md      # Project documentation
```

### 🔮 Future Enhancements
- Add machine learning NLP model (NLTK, spaCy)
- Add GUI using PyQt or Tkinter
- Add voice input/output integration
- Save conversation history
- Web interface (Flask/Django)
- Multi-language support
- Weather information integration
- News updates and web search capabilities

---

## Project 2: Language Translation Tool

### 🌐 Overview
A simple and elegant web-based language translator that allows users to translate text between 10 different languages in real-time using MyMemory Translation API.

### ✨ Features
* 🌍 **10 Languages Supported**: English, Hindi, Marathi, Spanish, French, German, Portuguese, Japanese, Chinese, and Arabic
* ⚡ **Real-time Translation**: Instant translation using MyMemory Translation API
* 🔊 **Text-to-Speech**: Listen to both source and translated text
* 📋 **Copy to Clipboard**: Easily copy translated text with one click
* 🔄 **Language Swap**: Quickly switch between source and target languages
* 🎨 **Clean UI**: Modern and responsive design

### 🗣️ Languages Available
1. English
2. Hindi
3. Marathi
4. Spanish
5. French
6. German
7. Portuguese
8. Japanese
9. Chinese
10. Arabic

### 🛠 Tech Stack

| Component | Used |
|-----------|------|
| Frontend | HTML5, CSS3, JavaScript (Vanilla) |
| API | MyMemory Translation API |
| Icons | Font Awesome |
| Speech | Web Speech API |
| Platform | Web Browser |

### 🚀 How to Use

1. **Open the Application**: Open `index.html` in your web browser
2. **Enter Text**: Type or paste the text you want to translate in the left textarea
3. **Select Languages**: Choose your source language (left dropdown) and target language (right dropdown)
4. **Translate**: Click the "Translate Text" button to get the translation
5. **Additional Features**:
   * Click the speaker icon 🔊 to hear the text
   * Click the copy icon 📋 to copy text to clipboard
   * Click the exchange icon 🔄 to swap languages

### 📁 Project Structure

```
CodeAlpha_Language Translation Tool/
│
├── index.html          # Main HTML file
├── style.css           # Styling for the application
├── js/
│   ├── script.js       # Main JavaScript logic
│   └── countries.js    # Language codes and names
└── README.md           # Project documentation
```

### 🌐 API Information
This project uses the **MyMemory Translation API**, which provides:
* Up to 10,000 words/day for free
* Support for multiple language pairs
* No API key required for basic usage

### 💻 Browser Compatibility
* ✅ Chrome (Recommended)
* ✅ Firefox
* ✅ Safari
* ✅ Edge
* ✅ Opera

**Note**: Text-to-speech feature requires browser support for the Web Speech API.

### 📦 Installation

1. Download or clone the project
2. No installation required - just open `index.html` in your browser
3. Make sure you have an internet connection for the translation API to work

### 🔮 Future Enhancements
- Add more languages
- Implement automatic language detection
- Add translation history
- Support for file translation
- Offline translation capability
- Dark mode toggle

---

## 🏆 CodeAlpha Internship

Both projects were developed as part of the **CodeAlpha Python Development Internship**. CodeAlpha is a learning platform that provides hands-on project experience to aspiring developers.

### 📝 Internship Tasks
- ✅ **Task 1**: Build a Simple Python ChatBot
- ✅ **Task 2**: Create a Language Translation Tool

---

## 👨🏻‍💻 Author

**Yash Mogal**  
AI Enthusiast  
*CodeAlpha Internship Program*

---

## 📄 License

Free to use for educational and personal projects.

---

## 🤝 Contributing

Feel free to fork these projects and add more features! Some ideas:
- Integrate chatbot with the translation tool
- Add more response patterns to chatbot
- Implement sentiment analysis
- Create mobile app versions
- Add user authentication
- Implement conversation logging

---

**Happy Coding! 🤖💜🌐**

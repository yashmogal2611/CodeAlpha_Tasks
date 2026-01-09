# B)Language Translation Tool

A simple and elegant web-based language translator that allows users to translate text between 10 different languages in real-time.

## Features

- **10 Languages Supported**: English, Hindi, Marathi, Spanish, French, German, Portuguese, Japanese, Chinese, and Arabic
- **Real-time Translation**: Instant translation using MyMemory Translation API
- **Text-to-Speech**: Listen to both source and translated text
- **Copy to Clipboard**: Easily copy translated text with one click
- **Language Swap**: Quickly switch between source and target languages
- **Clean UI**: Modern and responsive design

## Languages Available

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

## How to Use

1. **Open the Application**: Open `index.html` in your web browser
2. **Enter Text**: Type or paste the text you want to translate in the left textarea
3. **Select Languages**: Choose your source language (left dropdown) and target language (right dropdown)
4. **Translate**: Click the "Translate Text" button to get the translation
5. **Additional Features**:
   - Click the speaker icon 🔊 to hear the text
   - Click the copy icon 📋 to copy text to clipboard
   - Click the exchange icon 🔄 to swap languages

## Project Structure

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

## Technologies Used

- **HTML5**: Structure and layout
- **CSS3**: Styling and responsive design
- **JavaScript (Vanilla)**: Core functionality
- **MyMemory Translation API**: Translation service
- **Font Awesome**: Icons
- **Web Speech API**: Text-to-speech functionality

## API Information

This project uses the [MyMemory Translation API](https://mymemory.translated.net/doc/spec.php), which is a free translation service that provides:
- Up to 10,000 words/day for free
- Support for multiple language pairs
- No API key required for basic usage

## Browser Compatibility

- Chrome (Recommended)
- Firefox
- Safari
- Edge
- Opera

**Note**: Text-to-speech feature requires browser support for the Web Speech API.

## Installation

1. Download or clone the project
2. No installation required - just open `index.html` in your browser
3. Make sure you have an internet connection for the translation API to work

## Future Enhancements

- Add more languages
- Implement language detection
- Add translation history
- Support for file translation
- Offline translation capability
- Dark mode toggle

## Credits

Developed as part of CodeAlpha Internship Project

## License

Free to use for educational and personal projects.

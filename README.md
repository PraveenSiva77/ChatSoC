# ChatSoC - AI Powered Chatbot

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![OpenAI](https://img.shields.io/badge/AI-OpenAI-orange.svg)](https://openai.com/)

An advanced AI-powered chatbot developed by Team SquadofCreators as a 2nd Year Mini Project in Machine Learning. The project integrates multiple features including AI text generation, image generation, text-to-speech, QR code generation, YouTube downloads, and user authentication.

## ✨ Features

### 🤖 AI-Powered Capabilities

- **Text Generation** - Advanced conversational AI using OpenAI's GPT models
- **AI Image Generation** - Create images from text prompts using OpenAI's DALL-E
- **Text-to-Speech** - Convert text responses to natural-sounding audio
- **Intelligent Responses** - Context-aware conversations with temperature control

### 🔐 User Management

- **User Authentication** - Secure login system with CSV-based credential storage
- **User Registration** - New user signup with username/password validation
- **Version Control** - Support for free, owned, and subscribed user tiers
- **Session Management** - Persistent user sessions throughout interaction

### 🛠️ Utility Features

- **QR Code Generation** - Create QR codes for various data types
- **YouTube Downloader** - Download videos from YouTube using pytube
- **Wikipedia Integration** - Access Wikipedia articles and information
- **Speech Recognition** - Voice input capabilities for hands-free interaction
- **Web Browser Control** - Automated web browsing functionality

### 📱 Interactive Interface

- **Command-Line Interface** - User-friendly terminal-based interaction
- **Color-Coded Output** - Enhanced readability with colored text
- **Error Handling** - Comprehensive error management and user feedback
- **Multi-Modal Input** - Support for text and voice input methods

## 🛠️ Tech Stack

### Core Technologies

- **Python 3.8+** - Main programming language
- **OpenAI API** - AI text and image generation
- **pandas** - Data manipulation and CSV handling
- **pyttsx3** - Text-to-speech conversion
- **speech_recognition** - Voice input processing

### Libraries & Dependencies

- **PIL (Pillow)** - Image processing and manipulation
- **qrcode** - QR code generation functionality
- **opencv-python** - Computer vision and image processing
- **pyzbar** - QR code and barcode decoding
- **pytube** - YouTube video downloading
- **wikipedia** - Wikipedia API integration
- **requests** - HTTP requests handling
- **python-dotenv** - Environment variable management

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- OpenAI API key
- Required Python packages (see requirements below)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/PraveenSiva77/ChatSoC.git
   cd ChatSoC
   ```

2. **Install dependencies**

   ```bash
   pip install openai pandas pillow qrcode pyttsx3 wikipedia-api
   pip install webbrowser speech_recognition python-dotenv requests
   pip install pytube opencv-python pyzbar
   ```

3. **Set up environment variables**

   Create a `.env` file in the project root:

   ```env
   api_key=your_openai_api_key_here
   model=text-davinci-003
   ```

4. **Configure file paths**

   Update the CSV file path in `initial.py`:

   ```python
   path = "path/to/your/LoginCreditionals.csv"
   ```

5. **Run the application**

   ```bash
   python initial.py
   ```

### 🔑 API Setup

1. **OpenAI API Key**
   - Visit [OpenAI Platform](https://platform.openai.com/)
   - Create an account and generate an API key
   - Add the key to your `.env` file

2. **Model Configuration**
   - Choose your preferred OpenAI model
   - Update the model name in your `.env` file

## 🗂️ Project Structure

```text
ChatSoC/
├── ChatSoC/
│   ├── initial.py           # Main entry point and user authentication
│   ├── main.py             # Core AI functions and utilities
│   ├── myLibs.py           # Library imports and dependencies
│   ├── signup.py           # User registration functionality
│   ├── LoginCreditionals.csv # User credentials database
│   └── readme.txt          # Project notes and instructions
│
├── LICENSE                 # MIT License
└── README.md              # Project documentation
```

## 🎯 Usage

### Authentication

1. **Login** - Enter your username and password
2. **Signup** - Create a new account with version selection
3. **Version Types** - Free, Owned, or Subscribed access levels

### AI Features

- **Chat** - Engage in conversations with the AI
- **Image Generation** - Generate images from text descriptions
- **Voice Input** - Use speech recognition for hands-free interaction
- **Text-to-Speech** - Listen to AI responses

### Utility Functions

- **QR Codes** - Generate QR codes for text or URLs
- **YouTube Downloads** - Download videos for offline viewing
- **Wikipedia Search** - Access encyclopedia information
- **Web Browsing** - Automated web navigation

## 🔧 Configuration

### User Management

- Modify `LoginCreditionals.csv` to manage user accounts
- Update owned user IDs in `signup.py`
- Configure version-based access controls

### AI Settings

- Adjust `temperature` in `main.py` for response creativity
- Modify `max_tokens` for response length control
- Change image generation size parameters

### File Paths

- Update CSV file paths for your system
- Configure output directories for downloads
- Set appropriate working directories

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Contributors

### Praveenkumar S

- **Role**: Python Developer & AI Integration Specialist
- **GitHub**: [@PraveenSiva77](https://github.com/PraveenSiva77)
- **Contributions**: Core AI functionality, OpenAI integration, project architecture

### Sibi Siddharth S

- **Role**: Python Developer & Feature Implementation Specialist
- **GitHub**: [@sibisiddharth8](https://github.com/sibisiddharth8)
- **Contributions**: User authentication, utility features, system integration

## 🙏 Acknowledgments

- OpenAI for providing powerful AI APIs
- Python community for excellent libraries
- pytube developers for YouTube integration
- pyttsx3 team for text-to-speech functionality
- All open-source contributors whose libraries made this project possible

## ⚠️ Important Notes

- **API Keys**: Make sure to generate your own OpenAI API key
- **File Paths**: Update all file paths according to your system
- **Dependencies**: Install all required packages before running
- **CSV Data**: Modify login credentials as needed
- **Security**: Consider implementing proper password encryption for production use

## 📞 Contact

For any queries regarding the project:

- **GitHub**: [ChatSoC Repository](https://github.com/PraveenSiva77/ChatSoC)
- **Issues**: Report bugs and feature requests on GitHub

## 🚀 Future Enhancements

- Web-based user interface
- Database integration for user management
- Enhanced security with password encryption
- Real-time voice conversation capabilities
- Multi-language support
- Cloud deployment options

---

Made with ❤️ by Team SquadofCreators - 2nd Year ML Mini Project


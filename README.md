# 📢 Telegram BOT - Your AI-Powered Assistant

## 🚀 Features
This Telegram bot is an AI-powered assistant that provides multiple functionalities, including:

1. **🖼️ Image Analysis**  
   - Upload an image, and the bot will describe it using AI.
   - Supports `.jpg`, `.jpeg`, and `.png` formats.

2. **📂 File Reader & Summarizer**  
   - Reads and summarizes `.txt`, `.pdf`, and `.csv` files.
   - Extracts content and provides an AI-generated description.
   - Stores responses in a MongoDB database.

3. **📰 Latest News Search**  
   - Fetches real-time news from the internet on any topic.
   - Provides concise and relevant summaries.
   - Provides links to few news channels if user requires.

4. **💡 AI-Powered Query Answering**  
   - Ask any question, and the bot will generate an intelligent response using AI.

5. **🌍 Language Translation**  
   - Translate text to multiple languages.
   - Supports `/translate <language_code> <text>` format.

---
## Storage In MongoDB
 - Image summary
 - File summary
 - Chat interaction of user and bot

## 🔧 Installation & Setup
### **1️⃣ Prerequisites**
- Python 3.8+
- Telegram Bot Token
- MongoDB Database
- Google Gemini AI API Key

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Set Up Environment Variables**
Create a `.env` file and add:
```
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
GEMINI_API_KEY=your_gemini_api_key
MONGO_URI=your_mongodb_connection_string
```

### **4️⃣ Run the Bot**
```bash
python bot.py
```

---

## 📌 How to Use
- **Start the bot:** `/start`
- **Upload an image:** The bot will analyze and describe it.
- **Upload a file (.txt, .pdf, .csv):** The bot will extract content and summarize it.
- **Search latest news:** `/websearch <topic>`
- **Ask a question:** Send a text message, and the bot will reply.
- **Translate text:** `/translate <language_code> <text>`

---

## 🛠 Future Enhancements
- Support for `.docx` (Word files)
- OCR-based text extraction from scanned PDFs & images
- Improved language model for better responses

🚀 **Enjoy using the Telegram Bot!** 🎉


# 📝 Tableau Text Summarizer Extension

A powerful AI-powered extension that summarizes text data in your Tableau dashboards using OpenAI's GPT technology.

🌐 **Live Extension**: https://suryanshdev2023.github.io/tableau_text_summarizer_extension/

## 🚀 Quick Start

### Option 1: Use Hosted Version (Recommended)
1. **Download the manifest file**: [text_summarizer.trex](https://suryanshdev2023.github.io/tableau_text_summarizer_extension/text_summarizer.trex)
2. **In Tableau Desktop:**
   - Go to **Help → Settings and Performance → Manage Dashboard Extensions**
   - Add the downloaded `.trex` file to allowed extensions
   - Create a new dashboard and drag "Extension" object onto it
   - Select the `.trex` file when prompted
   - Enter your OpenAI API key and start summarizing!

### Option 2: Run Locally
1. **Double-click `start.bat`** (starts local web server)
2. **In Tableau Dashboard:**  
   - Add "Extension" object  
   - Select `text_summarizer.trex` file  
   - Enter OpenAI API key  
   - Choose worksheet/column  
   - Click "Summarize Text"

## 🔑 Get OpenAI API Key

Get your free API key at: https://platform.openai.com/api-keys

## ✨ Features

- **AI-Powered Summarization**: Uses GPT-4o-mini for intelligent text analysis
- **Easy Integration**: Works with any Tableau worksheet containing text data
- **Direct API Integration**: No CORS issues when used in Tableau Desktop environment
- **User-Friendly Interface**: Clean, modern UI with progress indicators
- **Flexible Text Length**: Handles large text datasets with smart truncation

## 🛠️ How It Works

1. **Select Worksheet**: Choose any worksheet from your Tableau dashboard
2. **Pick Text Column**: Select the column containing text data to summarize
3. **Enter API Key**: Provide your OpenAI API key (stored locally only)
4. **Get Summary**: Receive a concise 100-word summary of your text data

## 📋 Requirements

- Tableau Desktop 2018.2 or later
- OpenAI API key with available credits
- Text data in your Tableau worksheets
- Internet connection for API calls

## 🔒 Security & Privacy

- API keys are never stored or transmitted to our servers
- All processing happens client-side with direct OpenAI API calls
- HTTPS-secured connections ensure data protection

## 🆘 Troubleshooting

**Extension Not Loading?**
- Ensure the extension is added to Tableau's allowed extensions list
- Check that your Tableau version supports extensions (2018.2+)
- Try refreshing the dashboard

**API Connection Issues?**
- Verify your OpenAI API key is valid and has credits
- Check your internet connection
- The extension automatically tries multiple connection methods

**No Text Data Found?**
- Ensure your selected column contains string/text data
- Check that the worksheet has data rows
- Try a different text column

## 📞 Support

Created by **Suryansh Singh** at Piton Tech
- 📧 Email: suryansh.singh@piton-tech.de
- 🌐 Website: https://www.piton-tech.de

---

⭐ **Like this extension?** Give it a star on GitHub and share it with your team! 
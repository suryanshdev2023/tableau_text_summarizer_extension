# 🤖 Tableau GPT Assistant

A powerful AI-powered extension that connects your Tableau dashboards with GPT technology for intelligent data analysis, summarization, and insights generation.

🌐 **Live Extension**: https://suryanshdev2023.github.io/tableau_text_summarizer_extension/

## 🚀 Quick Start

### Option 1: Use Hosted Version (Recommended)
1. **Download the manifest file**: [text_summarizer.trex](https://suryanshdev2023.github.io/tableau_text_summarizer_extension/text_summarizer.trex)
2. **In Tableau Desktop:**
   - Go to **Help → Settings and Performance → Manage Dashboard Extensions**
   - Add the downloaded `.trex` file to allowed extensions
   - Create a new dashboard and drag "Extension" object onto it
   - Select the `.trex` file when prompted
   - Configure your AI settings and start analyzing!

### Option 2: Run Locally
1. **Double-click `start.bat`** (starts local web server)
2. **In Tableau Dashboard:**  
   - Add "Extension" object  
   - Select `text_summarizer.trex` file  
   - Configure AI settings  
   - Choose worksheet/column  
   - Click "Generate"

## 🔑 API Configuration

### OpenAI API
- **Get API Key**: https://platform.openai.com/api-keys
- **Model**: Use `gpt-4o-mini`, `gpt-4`, or any available model
- **Endpoint**: Leave blank (uses default OpenAI endpoint)

### Azure OpenAI API
- **Get API Key**: From your Azure OpenAI resource
- **Deployment**: Your Azure deployment name (e.g., `gpt-4-deployment`)
- **Endpoint**: Your Azure endpoint URL (e.g., `https://your-resource.openai.azure.com`)
- **API Version**: Use `2024-12-01-preview` or latest version

## ✨ Features

### 🤖 AI Capabilities
- **Universal AI Assistant**: Not just summarization - analyze, classify, generate insights
- **Custom Prompts**: Write your own prompts for any AI task
- **Rich Text Output**: Beautifully formatted results with headers, lists, and emphasis
- **Markdown Support**: AI responses are automatically formatted for readability
- **Token Management**: Smart truncation for large datasets

### 🔒 Security & Privacy
- **Data Encryption**: All sensitive data (API keys, endpoints) are encrypted before storage
- **Export Protection**: Encrypted data prevents exposure in exported `.twb` files
- **Local Storage**: Settings stored locally with localStorage fallback for external hosting
- **No Server Storage**: All processing happens client-side with direct API calls
- **HTTPS Secure**: All API communications are encrypted

### 🎨 User Experience
- **Modern UI**: Clean, professional interface with blue-to-mauve gradient theme
- **Format Toggle**: Switch between formatted and plain text views
- **Progress Indicators**: Real-time status updates and loading animations
- **Error Handling**: Comprehensive error messages and recovery options
- **Cross-Platform**: Works on local hosting and external servers (GitHub Pages, etc.)

### ⚙️ Configuration
- **Worksheet Selection**: Choose any worksheet from your dashboard
- **Column Picker**: Select text columns for analysis
- **System Role**: Define AI behavior and expertise
- **Token Limits**: Control processing costs and response length
- **Provider Support**: OpenAI and Azure OpenAI compatibility

## 🛠️ How It Works

1. **Configure Settings**: Set up your AI provider (OpenAI/Azure) and credentials
2. **Select Data Source**: Choose worksheet and text column from your dashboard
3. **Write Custom Prompt**: Define what you want the AI to analyze or generate
4. **Generate Analysis**: Get intelligent insights with beautiful formatting
5. **Toggle Views**: Switch between formatted and plain text as needed

## 📋 Use Cases

### 📊 Data Analysis
- **Trend Analysis**: "Identify trends in this sales data"
- **Pattern Recognition**: "Find patterns in customer feedback"
- **Insight Generation**: "Generate insights from survey responses"

### 📝 Content Processing
- **Text Summarization**: "Summarize these quarterly reports"
- **Classification**: "Categorize these support tickets"
- **Sentiment Analysis**: "Analyze sentiment in customer reviews"

### 🔍 Custom Tasks
- **Data Validation**: "Check for data quality issues"
- **Recommendations**: "Provide recommendations based on this data"
- **Report Generation**: "Create executive summary from this dataset"

## 🔒 Security Features

### Data Protection
- **Encryption Algorithm**: XOR encryption with base64 encoding
- **Protected Fields**: API keys, endpoints, deployment names, API versions
- **Export Safety**: Encrypted data appears as gibberish in exported workbooks
- **Local Storage**: Settings never leave your machine

### Privacy Compliance
- **No Data Collection**: We don't store or transmit your data
- **Direct API Calls**: All requests go directly to your chosen AI provider
- **User Control**: You control all data and API usage

## 🆘 Troubleshooting

### Extension Issues
**Extension Not Loading?**
- Ensure the extension is added to Tableau's allowed extensions list
- Check that your Tableau version supports extensions (2018.2+)
- Try refreshing the dashboard

**Settings Not Saving?**
- For external hosting (GitHub Pages), settings are saved to localStorage
- Check browser console for any error messages
- Try clearing browser cache and reloading

### API Connection Issues
**OpenAI API Problems?**
- Verify your API key is valid and has credits
- Check your internet connection
- Ensure you're using a supported model name

**Azure API Problems?**
- Verify your Azure OpenAI resource is active
- Check deployment name matches exactly
- Ensure API version is correct (try `2024-12-01-preview`)
- Verify endpoint URL format

### Data Issues
**No Text Data Found?**
- Ensure your selected column contains string/text data
- Check that the worksheet has data rows
- Try a different text column

**Large Dataset Issues?**
- Reduce token limit in settings
- The extension automatically truncates data if needed
- Consider filtering your data in Tableau first

## 📞 Support

Created by **Suryansh Singh** at Piton Tech
- 📧 Email: suryansh.singh@piton-tech.de
- 🌐 Website: https://www.piton-tech.de

---

⭐ **Like this extension?** Give it a star on GitHub and share it with your team! 
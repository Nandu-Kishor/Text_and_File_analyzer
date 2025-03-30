# 📝 AI-Powered Text & File Analyzer

A Gradio-based application that leverages **Google Gemini AI** to analyze and summarize text or uploaded files. It provides AI-generated insights with a user-friendly interface and downloadable results.

## 🚀 Features
- 🤖 **AI-Powered Analysis**: Uses Google Gemini AI for text processing.
- 📂 **Text & File Support**: Accepts manual text input or `.txt` file uploads.
- 📊 **Summary & Word Count**: Generates a concise summary with word count.
- 🔽 **Download Results**: Allows users to save analysis results as a file.
- 🎨 **Gradio UI**: Intuitive interface for seamless interaction.

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-text-analyzer.git
   cd ai-text-analyzer
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your Google API Key:
   ```bash
   export GOOGLE_API_KEY='your_api_key_here'
   ```

4. Run the application:
   ```bash
   python app.py
   ```

## 📌 Requirements
- Python 3.x
- Gradio
- Google Generative AI SDK

## 🎯 Usage
1. 📝 Enter text manually or upload a `.txt` file.
2. 🔍 Click "Analyze" to generate AI-driven insights.
3. 📊 View the summarized result and word count.
4. 💾 Download the analysis result for reference.

## 🔐 API Key Setup
This project requires a Google API key for Gemini AI. Replace the placeholder in `app.py` or set it as an environment variable.

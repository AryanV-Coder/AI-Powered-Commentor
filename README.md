# 💭 AI Powered Commentor

Deployed Link : https://ai-powered-commenter.streamlit.app/

This project is purely built on python using Streamlit framework and Gemini API.
You just need to select a Mood and click or upload your photo to it and then get an AI Powered comment.
Don't take the comment seriously as it is AI.

## 🚀 Setup Steps

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- A Google Gemini API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AryanV-Coder/AI-Powered-Commentor.git
   cd AI-Powered-Commentor
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up your Gemini API key**
   - Get your API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Create a `.env` file in the project root or configure it in Streamlit secrets
   - Add your API key to the configuration

5. **Run the application**
   ```bash
   streamlit run app.py
   ```

6. **Access the app**
   - Open your browser and navigate to `http://localhost:8501`
   - Select a mood, upload or capture a photo, and get your AI-powered comment!

### Troubleshooting
- If you encounter any package installation issues, ensure you have the latest version of pip: `pip install --upgrade pip`
- Make sure your Python version is compatible (3.8+)
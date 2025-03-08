# AI-Web-Scraper
An AI web scraper using ollama, brightdata, selenium and other libraries.

## 🚀 Features
- AI-powered web scraping
- Integration with Ollama for intelligent data processing
- Automated browser control using Selenium
- Proxy management with BrightData
- Streamlit-based user interface

## 📋 Prerequisites
- Python 3.9+
- Chrome/Firefox browser installed
- Git

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/AI-Web-Scraper.git
cd AI-Web-Scraper
```

2. Create and activate virtual environment:
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
```bash
# Create .env file and add your credentials
BRIGHTDATA_USERNAME=your_username
BRIGHTDATA_PASSWORD=your_password
OLLAMA_API_KEY=your_api_key
```

## 🎯 Usage

1. Start the Streamlit app:
```bash
streamlit run app.py
```

2. Open your browser and navigate to `http://localhost:8501`

3. Follow the UI instructions to start scraping

## 📝 Configuration
- Adjust scraping parameters in `config.yaml`
- Modify proxy settings in the BrightData dashboard
- Configure Ollama models in the settings panel

## ⚠️ Important Notes
- Ensure compliance with websites' terms of service
- Use appropriate delays between requests
- Monitor your proxy usage

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License
[MIT](https://choosealicense.com/licenses/mit/)


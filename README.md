# 📧 Cold Mail Generator

A Streamlit-based web application that generates personalized cold emails by analyzing job postings and matching them with relevant portfolio projects.

## 🚀 Features

- Web-based interface for easy interaction
- Automatic job posting analysis
- Skills extraction from job descriptions
- Portfolio project matching
- AI-powered email generation
- Clean and modern UI

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ColdMailGenerator.git
cd ColdMailGenerator
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
   - Create a `.env` file in the root directory
   - Add your API keys and configuration (refer to `.env.example` if available)

## 🏃‍♂️ Usage

1. Start the Streamlit application:
```bash
streamlit run main.py
```

2. Open your web browser and navigate to the provided local URL (typically http://localhost:8501)

3. Enter a job posting URL in the input field

4. Click "Submit" to generate a personalized cold email

## 📁 Project Structure

```
ColdMailGenerator/
├── main.py              # Main application entry point
├── chains.py            # LLM chain implementations
├── portfolio.py         # Portfolio management
├── utils.py            # Utility functions
├── vectorstore/        # Vector database storage
├── resources/          # Additional resources
└── requirements.txt    # Project dependencies
```

## 🔧 Dependencies

- langchain
- langchain-community
- langchain-groq
- unstructured
- selenium
- chromadb
- streamlit
- pandas
- python-dotenv

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 🙏 Acknowledgments

- Built with Streamlit
- Powered by LangChain
- Uses ChromaDB for vector storage

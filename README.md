# Medical Information Chatbot

A Retrieval Augmented Generation (RAG) based medical chatbot that provides accurate medical information by leveraging a medical knowledge base and Large Language Models.

## Overview
- Uses Pinecone vector database for efficient knowledge retrieval
- Powered by Google's Gemini Pro model for natural language understanding
- Built with LangChain for seamless integration
- Modern web interface for easy interaction

## Setup

1. Clone the repository
```bash
git clone <repository-url>
cd RAG
```

2. Create virtual environment
```bash 
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Set up environment variables in `.env`:
```
PINECONE_API_KEY=your_pinecone_key
GOOGLE_API_KEY=your_google_api_key
```

5. Run the application
```bash
python app.py
```

## Project Structure
```
RAG/
├── app.py                # Main Flask application
├── src/
│   ├── helper.py        # Helper functions
│   └── prompt.py        # Prompt templates
├── static/             
│   └── style.css        # CSS styling
├── templates/
│   └── chat.html        # Chat interface
├── research/
│   └── trials.ipynb     # Development notebooks
└── README.md
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

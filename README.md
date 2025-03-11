# Panaversity RAG

## Overview
Panaversity RAG (Retrieval-Augmented Generation) is a basic RAG system built using LangChain. It enables efficient retrieval of relevant information from documents and enhances responses using LLMs.

## Features
- Uses LangChain for retrieval-augmented generation
- Processes and embeds documents for efficient querying
- Integrates with a language model to generate contextual responses
- Modular design for easy expansion and customization

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Panaversity_RAG.git
   cd Panaversity_RAG
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Setup
1. **Configure API Keys:**
   - Store API keys in a `.env` file and add it to `.gitignore`.
   - Example `.env` file:
     ```env
     OPENAI_API_KEY=your_api_key_here
     ```
   - Load these keys securely in your script using `dotenv`:
     ```python
     from dotenv import load_dotenv
     import os

     load_dotenv()
     OPENAI_API_KEY = os.getenv("OPENAI_API_KEY")
     ```

## Usage
1. Run the Jupyter Notebook:
   ```sh
   jupyter notebook Panaversity_RAG.ipynb
   ```
2. Follow the notebook instructions to process documents and generate responses.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss proposed modifications.

## License
This project is licensed under the MIT License.

## Contact
For any questions, reach out via GitHub Issues.

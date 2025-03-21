# Text to Math Problem Solver and Data Search Assistant
- This is a Streamlit-based web application that utilizes LangChain and Google Gemma 2 to solve mathematical problems and retrieve data from Wikipedia. The application integrates various tools to assist users in solving mathematical queries, logical reasoning questions, and retrieving relevant information from Wikipedia.

# Features
- Math Problem Solver: Uses LangChain's LLMMathChain to solve mathematical expressions with detailed step-by-step explanations.
- Wikipedia Search Tool: Retrieves relevant information from Wikipedia based on user queries.
- Reasoning Assistant: Provides logical reasoning and explanation for complex questions.
- Conversational Interface: Maintains chat history for an interactive user experience.

# Technologies Used
- Streamlit: For building the web application UI.
- LangChain: For integrating LLM capabilities.
- Google Gemma 2 (via Groq API): As the main language model.
- Wikipedia API Wrapper: For searching Wikipedia.
- LangChain Agents: For dynamically selecting tools based on user input.

# Installation
1. Clone this repository:
   - git clone https://github.com/your-username/repo-name.git
   - cd repo-name
2. Create a virtual environment:
  - python -m venv env
  - source env/bin/activate
3. Install dependencies:
  - pip install -r requirements.txt
4. Run the application:
  - streamlit run app.py

# Usage
- Enter your Groq API key in the sidebar.
- Type your question in the input box.
- Click on "Find My Answer" to generate a response.
- The assistant will respond with the solution or relevant data from Wikipedia.

# File Structure
- repo-name/
- │── app.py                  # Main Streamlit application
- │── requirements.txt        # Required dependencies
- │── README.md               # Project documentation

# Requirements
Ensure you have the following installed:
- Python 3.8+
- Streamlit
- LangChain
- Wikipedia API Wrapper
- Groq API Key (required for ChatGroq model)
- Tools and Agents

# Contributing
- Feel free to fork this repository and submit a pull request with any improvements or bug fixes.

# Author
Developed by Prathik M Hadagali.

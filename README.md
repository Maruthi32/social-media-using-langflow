# Social Media Performance Analysis

A basic analytics module utilizing Langflow and DataStax to analyze engagement data from mock social media accounts and Streamlit-based web application that allows users to interact with a flow generated by LangFlow for social media performance analysis.

## Used Tools:
● DataStax Astra DB for database operations.

● Langflow for workflow creation and GPT integration.

● Streamlit for frontend access of Langflow.

## Features

- Powered by **LangFlow** and **DataStax** for robust and accurate analysis.
- Interactive chat interface for social media performance analysis.
- Easy-to-use interface with real-time insights from LangFlow.

---

## Setup Instructions

### 1. Clone the Repository
```bash
https://github.com/Maruthi32/social-media-using-langflow.git
cd social-media-using-langflow
```

### 2. Create a Virtual Environment
Set up a Python virtual environment to manage dependencies:
```bash
python -m venv env

```
Activate the virtual environment:
On Windows:
```bash
source env/Scripts/activate
```
On Mac/Linux:
```bash
source env/bin/activate
```

### 3. Install Dependencies
Install the required Python libraries:

```bash
pip install -r requirements.txt
```
### 4. Replace Application token

Replace "Application token" in main.py with the API token generated by LangFlow.

### 5. Run the Application
Start the Streamlit application:

```bash
streamlit run main.py
```

## How to Use
(1) Enter your query in the text area provided.

(2) Click on the "Analyse" button to analyze the query.

View the analysis result along with the chat history displayed below the input area.

## Project Structure
- main.py: Main application file containing the Streamlit app logic.
- requirements.txt: List of dependencies required for the project.

## Notes
Ensure you have a valid LangFlow APP_TOKEN before running the application.

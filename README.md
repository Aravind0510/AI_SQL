
# AI_SQL_12

## Overview
**AI_SQL_12** is an AI-driven SQL assistant that enhances interactions with SQL databases. It uses generative AI to convert natural language queries into SQL statements, execute them, and display the results in an intuitive interface. This tool simplifies complex database operations, making data retrieval and analysis more accessible.

## Features
- **Natural Language to SQL**: Converts user inputs into SQL statements using AI.
- **Intelligent Error Handling**: Provides suggestions for correcting SQL errors.
- **Conversation Memory**: Maintains context across queries for smoother interactions.
- **Visual Outputs**: Displays results in a readable format, including tables and charts.

## Installation

1. **Install Required Dependencies**
   Ensure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
### 1. Running the Application
Start the application with:
```bash
streamlit main2.py
```
This will launch the Streamlit interface where you can interact with the AI SQL Assistant.

### 2. Using the AI SQL Assistant
- **Home**: Introduction and overview of the assistant's capabilities.
- **AI-SQL**: Interact directly with the AI SQL Assistant. Enter natural language queries, and the assistant will generate and execute SQL statements.
- **Schema**: View schema details to understand the database structure.

### 3. Starting a New Chat
- Click the "New Chat" button to reset the session and start a fresh interaction.

### 4. Downloading Results
- You can download the results of your queries directly from the interface.

## Code Structure
- **`main2.py`**: The main script that runs the Streamlit application and manages user interactions.
- **`sql_execution.py`**: Handles execution of SQL queries against the database.
- **`trialprompt.py`**: Contains AI prompt templates used for guiding the AI's responses.
- **`schemex1.py`**: Manages the schema information for database tables.

## Environment Variables
Before running the application, ensure you set up your environment variables correctly:
- **`OPENAI_API_KEY`**: Set your OpenAI API key in the `main2.py` file.

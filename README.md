# Chat With MySQL

**Chat With MySQL** is an AI-powered assistant that converts user queries into SQL commands and interacts with a MySQL database. Built with **Streamlit** and **LangChain**, it uses **ChatGroq's Llama3-8b-8192** model to generate SQL and provide context-aware responses, enabling users to query data without SQL knowledge.

## Features
- Conversational interface to interact with MySQL databases.
- Converts natural language queries into SQL commands.
- Retrieves and displays database query results.
- Built using **Streamlit**, **LangChain**, and **ChatGroq's Llama3-8b-8192** model.
- No SQL expertise required.

## Prerequisites
- Python 3.7+
- MySQL database
- **.env** file with `GROQ_API_KEY` for ChatGroq model access.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Chat-With-MySQL.git
   cd Chat-With-MySQL

2. Install required packages:
   ```bash
   pip install -r requirements.txt

3. Create a .env file in the root directory and add your GROQ_API_KEY:
   ```bash
   GROQ_API_KEY=your_groq_api_key

## Usage

1. Run the app:
   ```bash
   streamlit run app.py

2. In the sidebar, enter the MySQL database credentials:

   - Host
   - Port
   - User
   - Password
   - Database

3. Click Connect to establish a connection to the database.

4. Start chatting with the AI assistant by typing your SQL-related queries.

   

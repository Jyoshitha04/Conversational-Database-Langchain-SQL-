# Conversational Database using LangChain and SQL  

## 📌 Overview  
This project is a **Conversational Database System** that allows users to interact with a SQL database using **natural language** instead of writing SQL queries manually.  
The application uses **LangChain** to translate plain English queries into SQL, executes them on the database, and returns results in a conversational format.  

This makes database access **easier, faster, and more user-friendly**, especially for non-technical users.  

---

## 🚀 Features  
- ✅ Convert **natural language** into SQL queries  
- ✅ Query execution on a MySQL database  
- ✅ Conversational response format  
- ✅ Error handling for invalid queries  
- ✅ Extendable to other databases (PostgreSQL, SQLite, etc.)  
- ✅ Simple and modular project structure  

---

## 🛠️ Tech Stack  
- **Programming Language:** Python  
- **Framework & Libraries:**  
  - [LangChain](https://www.langchain.com/) – for LLM-powered query generation  
  - [MySQL Connector](https://dev.mysql.com/doc/connector-python/en/) – for database connection  
  - [OpenAI API](https://platform.openai.com/) – for natural language understanding (if configured)  
- **Database:** MySQL

  ## 🖥️ Usage  

Once the app is running, you can ask database questions in **natural language**, for example:  

- *"Show me the top 5 customers with the highest purchases"*  
- *"What is the average salary of employees in the IT department?"*  
- *"List all products sold in the last 30 days"*  

The system will:  
1. Convert your question into an **SQL query**  
2. Execute it on the **database**  
3. Return the results in a **conversational format**  

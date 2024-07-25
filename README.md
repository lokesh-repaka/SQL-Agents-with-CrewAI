
# SQL-Powered AI Analyst with CrewAI

Welcome to the SQL-Powered AI Analyst project! This project leverages the CrewAI framework to create a team of collaborative AI agents that can directly interact with SQL databases to answer complex data questions.

## Overview

This system transforms user queries into SQL statements, retrieves the data, analyzes it, and generates a comprehensive report. It's designed to streamline data analysis processes, making it faster and more efficient.

## Features

- **Direct SQL Integration:** The AI agents connect directly to SQL databases for real-time data retrieval.
- **Specialized Agents:**
  - **Database Developer Agent:** Constructs and executes SQL queries based on natural language input.
  - **Data Analyst Agent:** Analyzes the query results to extract patterns and insights.
  - **Report Writer Agent:** Summarizes the findings into a concise, readable report.
- **Powered by Llama 3 LLM:** Utilizes advanced language models to understand and process natural language queries, enhancing the capabilities of each agent.
- **Scalability and Efficiency:** Designed to handle large datasets and complex queries efficiently.

## Workflow

1. **User Query:** A user submits a question in natural language.
2. **SQL Query Generation:** The Database Developer Agent translates the question into an SQL query.
3. **Data Retrieval:** The query is executed on the connected SQL database.
4. **Data Analysis:** The Data Analyst Agent processes the retrieved data, identifying key insights.
5. **Report Generation:** The Report Writer Agent compiles the insights into a human-readable report.

![Crew AI SQL Agent](https://github.com/user-attachments/assets/b306590f-774c-4f97-8dcc-e40dcd5b3911)

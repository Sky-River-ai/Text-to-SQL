A large language model trained to convert natural language queries into SQL statements. 
I used the LangChain agent to create a chain that combines the LLM with a prompt template and a MySQL execution function. 
The prompt template will guide the LLM in generating SQL queries based on the user's natural language input.
The execution function will execute the generated SQL query against MySQL database.

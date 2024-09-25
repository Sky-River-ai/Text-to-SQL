A large language model trained to convert natural language queries into SQL statements. 
I used the LangChain agent to create a chain that combines the LLM with a prompt template and a MySQL execution function. 
The prompt template will guide the LLM in generating SQL queries based on the user's natural language input.
The execution function will execute the generated SQL query against MySQL database.
Also used below mentioned libraries,
Sentence-Transformers: A library for sentence embeddings, crucial for semantic similarity calculations and efficient vector database operations.
ChromaDB: A powerful vector database optimized for similarity search, providing efficient storage and retrieval of embeddings.
LangChain-Experimental: Access to experimental features and components within the LangChain ecosystem, allowing you to explore cutting-edge capabilities.
TikToken: A library for tokenizing text, essential for understanding and processing natural language input.
FAISS-CPU: A fast approximate nearest neighbor search library, useful for efficient similarity searches in large-scale vector databases.
Protobuf: A protocol buffer compiler, often used for serializing structured data, which might be relevant in certain scenarios.
Python-Dotenv: A library for loading environment variables from .env files, useful for managing sensitive information like API keys.

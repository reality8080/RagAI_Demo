# RagAI_Demo

Invoke-WebRequest https://github.com/milvus-io/milvus/releases/download/v2.4.15/milvus-standalone-docker-compose.yml -OutFile docker-compose.yml

docker compose up -d
pip install pymilvus

pip install pymilvus==2.3.5 langchain langchain-text-splitters langchain-milvus langchain-google-genai sentence-transformers transformers torch psycopg2-binary python-dotenv

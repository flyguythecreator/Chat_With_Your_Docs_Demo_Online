# Chat with Your Docs with RAG Models Demo

Here we will be building a RAG + Langchain Python Model for an easy chat with your data chatbot interface.

The source of the starting code can be found here: [https://www.youtube.com/watch?v=tcqEUSNCn8I]

This Repo consists of a dependency requirements file for you to install with `pip3 install -r requirements.txt`. Starter data using **Alice in Wonderland** book. Local vector database creation file (You will need to create the **chroma** folder separately). Vector embedding evaluation file and the data querying file.

## The order to run the files to experience the best results

1. Run `pip3 install -r requirements.txt` in terminal of repository.

2. Run `mkdir chroma`.

3. Store **OPENAI_API_KEY** in .env file.

4. Run `python3 create_databases.py`.

5. Run `python3 compare_embeddings.py`.

6. Run `python3 query_data.py query_text YOUR_QUESTION_FOR_THE_MODEL`.

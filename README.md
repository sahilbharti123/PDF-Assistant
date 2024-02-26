# PDF Assistant Chatbot

This is a chatbot assistant that can read PDFs and answer questions about their content.

## Overview

The chatbot uses the llama_index library to index a folder of PDFs. It can then take a natural language query, search the index for relevant passages from the PDFs, and return an excerpt summarizing the answer.

## Some key components:

- SimpleDirectoryReader to read PDF contents into documents
- VectorStoreIndex to index the documents and store embeddings
- VectorIndexRetriever to search the index for relevant passages
- RetrieverQueryEngine to handle queries and retrieve responses

## Usage

To use the chatbot:

- Install dependencies
- Add PDFs to the pdfs/ folder
- Run the Jupyter notebook
- Pass a query to the search_engine to get a response

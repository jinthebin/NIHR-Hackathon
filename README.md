# Semantic Search RAG web app, for querying Healthcare research records as maintained by the NIHR 
 Program to run on Semantic similarity in following process:
1.  Fetches data from API in JSON format (publicly available)
2.  Uses Langchain - Huggingface embeddings for sentence embeddings
3.  Parses Textual data as vectors and stores them in ChromadB vector local storage
4.  Calls Gemini API to find semantic similarity to user prompt with dB to return results

# Gemini API to be swapped out with Gemma or LLAMA or Spacy, providing Open-Source application. 
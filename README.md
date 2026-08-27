# Ragify: Business Analytics AI with RAG

Ask a plain-English business question, get a precise SQL answer, with unstructured context (user reviews) blended in through vector retrieval.

- Natural language to SQL over a structured database via a LangChain pipeline (OpenAI API; Ollama for local runs)
- Unstructured data (reviews) indexed in Pinecone and retrieved by similarity search
- Notebooks: `Excel_to_sqlite.ipynb` (data prep), `NL_to_SQL.ipynb` (main pipeline), `openAI_basic_chain_call.ipynb` (chain basics)

Final-year project at VIT Vellore (2024-25). Filed by VIT as Indian patent application 202541118370, "AI-Powered Business Insights Assistant Using RAG" (examination pending).

Built by [Patel Tirth](https://ptirth.dev/#ragify).

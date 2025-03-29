# "GolfGPT" Building a Chatbot that helps you learn how to golf, using Retrieval Augmented Generation.
"GolfGPT" is a chatbot that helps you learn how to golf.  Buildt Chatbot using OpenAI Embeddings, OpenAI API, RAG, Langflow and Astra vector database

<br>

<h2>Features</h2>

1. Knowledge Base Creation:
Used LangFlow to upload, process, and store large .pdf document directly in a vector database.
Built the entire knowledge base dynamically without preloading or external scripts.

2. Document Processing and Embedding Generation:
LangFlow split the document into manageable chunks and generated embeddings using Nvidia's NV-Embed-QA
text-embedding model.
Stored embeddings seamlessly in Astra DB for efficient vector-based retrieval.

3. Agentic Query and Retrieval:
Dynamically retrieved relevant data from the knowledge base using LangFlow's Retriever flow.
Empowerwed the chatbot with contextual understanding for golf-specific queries.

4. Interactive Chatbot:
Built an OpenAI chatbot capable of answering user queries by accessing the knowledge base created within LangFlow.
Ensured precise and contextually accurate responses tailored to user needs. 

<h2>Use Cases</h2>
<li>Questions about pdf document(s): Build a chatbot that retrieves information from .pdf document(s).</li>
<li>Questions/queries about Corporate documents: company benefits program, company policies, onboarding, etc.</li>
<li>Interactive FAQ Systems: Create a system that provides instant answers to user queries for businesses or organizations.</li>
<li>Knowledge Management: Enable semantic search and retrieval for dynamically uploaded documents in enterprise environments.</li>

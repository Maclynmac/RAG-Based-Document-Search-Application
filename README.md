<strong>Agentic RAG System for Intelligent Document Analysis</strong>

<strong>Features:</strong>

<ul>
  
<li>Agentic RAG search for answering questions from documents </li>

<li>Web URL and local file document ingestion </li>

<li>Automatic document chunking and splitting</li>

<li>Semantic search using embeddings and FAISS </li>

<li>LangGraph-based retrieval and response workflow</li>

<li>ReAct-style agent behavior with document and Wikipedia tools</li>

<li>Command-line interface and Streamlit web UI</li>

<li>Source document display and recent query history</li>

</ul>


<strong>Technologies Used:</strong>
<ul>
<li>Python – Used as the main programming language for developing AI.</li>
<li>LangChain - Abstracts complexity of working with LLMs and Provides pre-built components (document loaders, text splitters, chains).
    Standardized interfaces for different LLM providers.Simplifies prompt management and chain orchestration.</li>
<li>LangGraph –Enables multi-step workflows with clear data flow and state management. Perfect for RAG pipelines (retriever → responder pattern). Handles branching and complex agentic logic.Better than simple chains for stateful applications</li>
<li>OpenAI GPT-4o - Best-in-class reasoning and answer quality.Strong context understanding for synthesizing answers from retrieved documents.Industry standard trusted by enterprise applications </li>
<li>OpenAI Embeddings - Used to convert text into vector representations for semantic search and retrieval. High-quality semantic understanding for retrieval </li>
<li>FAISS – Used to efficiently store and search vector embeddings for similarity matching. Fast, efficient vector similarity search at scale</li>
<li>Streamlit – Used to build interactive web interfaces for AI applications quickly.</li>
<li>Pydantic –Type-safe data validation for workflow state and Catches bugs early (invalid data types, missing fields).Clear schema definition for RAGState.Improves code reliability and IDE support</li>
<li>ReAct Agent Pattern -  Enables intelligent reasoning before tool use.Allows intelligent tool selection (when to use retriever vs. Wikipedia) and More human-like problem-solving approach</li>
</ul>

# Output

<img width="5356" height="2392" alt="IMG-20260702-WA0294" src="https://github.com/user-attachments/assets/a1c76bd0-9f84-489b-ac4c-f5d47009fbc4" />


<img width="5324" height="2540" alt="IMG-20260702-WA0287" src="https://github.com/user-attachments/assets/5d2f96e8-758b-489b-8f4d-8aa2e1045330" />


<img width="5416" height="2660" alt="IMG-20260702-WA0267 (1)" src="https://github.com/user-attachments/assets/2e85dcb6-9417-4b0a-96cc-3277e2cc1298" />


<img width="5324" height="2684" alt="IMG-20260702-WA0272" src="https://github.com/user-attachments/assets/b136117d-dab9-4772-8d15-f323a51c44f5" />


<img width="5428" height="2660" alt="IMG-20260702-WA0274 (1)" src="https://github.com/user-attachments/assets/b5e6e70f-e9f7-480e-a060-3f8eaf842a25" />


















<strong> RAG-Based-Document-Search-Application </strong>

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
<li>LangChain – Abstracts complexity of working with LLMs and Provides pre-built components (document loaders, text splitters, chains).Standardized interfaces for different LLM providers.Simplifies prompt management and chain orchestration.</li>
<li>LangGraph –Enables multi-step workflows with clear data flow and state management. Perfect for RAG pipelines (retriever → responder pattern). Handles branching and complex agentic logic.Better than simple chains for stateful applications</li>
<li>OpenAI GPT-4o - Best-in-class reasoning and answer quality.Strong context understanding for synthesizing answers from retrieved documents.Industry standard trusted by enterprise applications </li>
<li>OpenAI Embeddings - Used to convert text into vector representations for semantic search and retrieval. High-quality semantic understanding for retrieval </li>
<li>FAISS – Used to efficiently store and search vector embeddings for similarity matching. Fast, efficient vector similarity search at scale</li>
<li>Streamlit – Used to build interactive web interfaces for AI applications quickly.</li>
<li>Pydantic –Type-safe data validation for workflow state and Catches bugs early (invalid data types, missing fields).Clear schema definition for RAGState.Improves code reliability and IDE support</li>
<li>ReAct Agent Pattern -  Enables intelligent reasoning before tool use.Allows intelligent tool selection (when to use retriever vs. Wikipedia) and More human-like problem-solving approach</li>
</ul>









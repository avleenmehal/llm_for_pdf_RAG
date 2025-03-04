**LOCAL LLM LLAMA2 model with RAG implementation for PDF summarization**

I am a grad student who have multiple pdf files for a single course and to prepare for a midterm it was difficult to go through all in short time. 
It was even difficult to provide the online llm tools all the pdf files to summarize it for me.

So I created a local LLM project using RAG which helps with the accuracy of the questions that i might have regarding the course curriculum.

Therefore I used chroma DB as my vector database used for providing the LLM model with context using which we can have augmented generation for the respones.

**MODEL** - Ollama LLama2 / Mistral
**VECTOR DB** - Chroma DB for RAG
**EMBEDDING** - OllamaEmbedding
**TESTING** - Test cases for the summarization of the pdf files using the llm itself

**FUTURE**
I will try to open a OPENAI account and use the GPT model to have more accurate responses.

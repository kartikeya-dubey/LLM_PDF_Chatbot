# LLM_PDF_Chatbot

Implementation Video: https://go.screenpal.com/u/ALU6/PDF-chatbot

Python project to chat with multiple input PDF documents, using Streamlit : GUI and Cohere : LLM

Integrated memory (ConversationBufferMemory) and chat history for more human experience.

This app accepts multi-page pdf documents > divides pdf pages to chunks (langchain.text_splitter ) > embeds (langchain_community.embeddings.cohere) and creates a vectorstore (FAISS) which serves as knowledge context for the LLM.

Used LangSmith to trace llm calls and analyse code fails.

> [!NOTE]
> For codes, you may request collaboration on kartikeyadubey1997@outlook.com.

# AI-Powered-HR-assistant
A conversational chatbot that responds to user inquiries using PD0F document information. Extracts and converting text into numerical vectors, establishing an answer-finding mechanism, and designing a user-friendly chatbot interface with Gradio to deploy the chatbot
This script creates a Retrieval-Augmented Generation (RAG) chatbot that answers questions about the Nestlé HR Policy PDF.

-Reads OpenAI API key from a text file.
-Loads the Nestle HR PDF.
-Cleans and chunks the text for embedding.
-Builds a vector database (Chroma) for semantic search.
-Uses OpenAI embeddings to encode text.
-Retrieves relevant chunks when a user asks a question.
-Sends the retrieved context and user question to OpenAI LLM.
-Wraps everything in a Gradio Chat UI.

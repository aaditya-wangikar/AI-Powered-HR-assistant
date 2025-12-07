# AI-Powered-HR-assistant
A conversational chatbot that responds to user inquiries using PD0F document information. Extracts and converting text into numerical vectors, establishing an answer-finding mechanism, and designing a user-friendly chatbot interface with Gradio to deploy the chatbot
This script creates a Retrieval-Augmented Generation (RAG) chatbot that answers questions about the Nestlé HR Policy PDF.

1. Reads OpenAI API key from a text file. Note: Create a text file API_KEY.txt and copy your openai api key
2. Loads the Nestle HR PDF.
3. Cleans and chunks the text for embedding.
4. Builds a vector database (Chroma) for semantic search.
5. Uses OpenAI embeddings to encode text.
6. Retrieves relevant chunks when a user asks a question.
7. Sends the retrieved context and user question to OpenAI LLM.
8. Wraps everything in a Gradio Chat UI.

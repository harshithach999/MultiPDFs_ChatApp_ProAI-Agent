# MultiPDFs_ChatApp_ProAI-Agent
An advanced Streamlit-based application that lets you chat with multiple PDFs or TXT files using LangChain, Google Gemini Pro, and FAISS for accurate, context-aware responses.
MultiPDFs_ChatApp_ProAI-Agent

Meet MultiPDF Chat AI App — a powerful tool to chat seamlessly with multiple PDFs using LangChain, Google Gemini Pro, and FAISS Vector DB, with streamlined deployment through Streamlit. Get instant and accurate responses from advanced language models, transforming the way you interact with your documents.

Description
The Multi-PDF's Chat Agent is a Streamlit-based web application that enables interactive conversations with a chatbot trained on multiple PDF or TXT documents. Users can upload documents, extract their text, and interact with the chatbot in real-time based on the extracted content.

How It Works

PDF Loading – Reads and extracts text from multiple documents.

Text Chunking – Splits extracted text into manageable chunks for processing.

Language Model – Generates vector embeddings of the text chunks.

Similarity Matching – Matches user queries with semantically similar chunks.

Response Generation – Produces context-aware responses using relevant document content.

Key Features

Adaptive Sliding Window Chunking for optimized RAG performance.

Multi-document conversational QA, including multi-hop queries.

Supports PDF and TXT formats.

Works with Google Gemini Pro, OpenAI GPT-3, Anthropic Claude, LLaMA2, and other LLMs.

Requirements

Streamlit – For building the web interface.

google-generativeai – For generative AI capabilities.

python-dotenv – For managing environment variables and configuration.

langchain – For NLP pipelines, embeddings, vector stores, and conversational retrieval.

PyPDF2 – For PDF reading and manipulation.

faiss-cpu – For efficient similarity search and vector operations.

langchain_google_genai – For integrating LangChain with Google’s generative AI SDK.
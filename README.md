# QORAbot
Project Summary:
QORAbot aims to make NASA’s scientific information and research more accessible through an intelligent chat interface. The project provides users with accurate answers supported by real text and references directly retrieved from NASA’s official website.

Practical Work Steps:

Data Collection: Gathered raw data manually and through web scraping from NASA’s official website.

Structuring and Organization: Arranged the data into a well-structured format with five main columns for easier processing (e.g., title, source, date, summary, and full text).

Data Cleaning and Processing: Removed duplicates, standardized formats, cleaned text, and performed document chunking to prepare for indexing.

Building a Complete RAG System: Split documents into smaller chunks, generated vector embeddings for each, and stored them in a Vector Database for similarity-based retrieval.

Integration with LLMs: Upon receiving a user query, the system retrieves the most relevant documents from the Vector DB → passes them to the LLM with a custom-designed prompt → and generates a final answer supported by source citations.

Testing and Evaluation: Tested the system with real-world questions and scenarios to ensure the accuracy and relevance of the generated responses and research displays.

Results and Impact:

Developed a chatbot capable of answering questions about NASA’s research and scientific information with higher precision than traditional text search, since it references the original sources directly.

Useful as an educational and research tool for fast and reliable access to references and scientific papers.

Amar Ahmed
Data scientist | Machine Learning Developer | Computer Vision Researcher

linkedin: https://www.linkedin.com/in/amar-ahmed-25b676302/ 


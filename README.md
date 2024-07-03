**Simple RAG program**

The code uses OpenAI (GPT-4) to create a model that can answer questions based on any PDF. It loads and parses a PDF, after which the parsed file is turned into embeddings. After that, a pipeline is created which takes the PDF embeddings, the questions and returns an answer tailored to specific PDF using GPT-4

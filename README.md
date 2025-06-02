# Project overview

This project involved designing and building a question-answering agent for Healthym, a fictional company in the healthy foods market. The goal was to simulate a real-world use case where a virtual assistant can accurately answer questions about a company’s products, recipes, and suppliers by retrieving relevant context from a structured knowledge base.

All the data used as the knowledge base for the agent was created using a synthetic text data generator. This generator was built using an open source large language model. The data generated is composed of 69 text documents contains information about the company description, its products, recipes and suppliers. To know more about the generator, how it works or to use it on you own projects, please consult the page: https://github.com/diogofn1/Synthetic-Text-Data-Generator

# Technologies & Tools
- **Programming language:** Python
- **Development environment:** Jupyter Notebook
- **Libraries & frameworks:**
  - **Data generation:** Tranformers, torch, OPENAI
  - **Data processing:** langchain, OPENAI 
  - **Database storage**: Croma
  - **User interface / Model deployment**: Gradio
 
# Skills employed in the project
- **Synthetic Data Generation:** Developed a synthetic dataset using an open-source LLM to simulate realistic business knowledge.
- **Data Engineering:** Structured and indexed unstructured documents in a vector database for scalable search and retrieval.
- **Natural Language Processing:** Applied embedding techniques and retrieval pipelines for effective context-based QA.
- **Generative AI:** Built a question-answering agent using Retrieval-Augmented Generation (RAG).
- **Product Design & Prototyping:** Created an end-to-end interactive demo that simulates a customer-facing product.
- **Documentation & Communication:** Delivered clean, well-documented code and concise summaries to explain the work that was done.


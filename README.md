# Project overview

The objective of this project was to build a question answering agent for the company Healthym. Healthym is a fictional company in the healthy foods market. The agent should be able to ask questions about the company and its products by consulting a knowledge database and generanting and use it as a context to provide a answer to a user.

All the data used as the knowledge base for the agent was created using a synthetic text data generator. This generator was built using an open source large language model. The data generated contains information about the company description, its products, recipes and suppliers and is composed of 69 textual documents. To know more about the generator, how it works or to use it on you own projects, please consult the page: https://github.com/diogofn1/Synthetic-Text-Data-Generator

# Technologies & Tools
- **Programming language:** Python
- **Development environment:** Jupyter Notebook
- **Libraries & frameworks:**
  - **Data generation:** Tranformers, torch, OPENAI
  - **Data processing:** langchain, OPENAI 
  - **Database storage**: Croma
  - **User interface / Model deployment**: Gradio
 
# Skills employed in the project
- **Data geration:** preprocessing the dataset through data cleaning, transformation, and handling imbalanced data for effective modeling.
- **Machine learning:** use of large language models for synthetic data generation, text embedding, and natural language processing.
- **Generative AI**: building a chat agent using Retrieve Augmented Generation.
- **Documentation:** synthesizing the work through organized code and concise textual summaries.


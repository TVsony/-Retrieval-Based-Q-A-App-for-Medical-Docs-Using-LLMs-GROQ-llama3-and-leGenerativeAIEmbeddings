# Project: "Retrieval-Based Q&A App for Medical Documentation"

Build Q&A system for Medical field that uses to pull from various medical documents. Stack Overflow answeres or internal docs and Knowlege bases as needed.
Such an API app can summarize and clarity complex concepts or answer specific Medical Questions.

**Key component in this project include:**

- Groq Model -->llama3
- GoogleGenerativeAIEmbeddings ---->models/embedding-001
- Open source LLMs for interpreting questions and generating Answers
- Integration with APIs for external sources such as GoogleGenrativeAIEmbedding

API gives an instatant high quality reliable answer responce to medical questions without manually searching through large docs. This can be especially helpfull for Medical student and other medical propfessionals where the docs are extensive

## TO Run this API

Streamlit run app.py
Click on
Document Embedding --> wait moments
When vectors Strore db Ready then

Take a Question from Document or
Enter Your Question Document
press enter
Finally you will see response of model

**More info about the API**
useful for different purposes in AI, natural language processing, cloud integration, and web app development

1.FAISS (CPU): FAISS (Facebook AI Similarity Search) is a library for efficient similarity search and clustering of dense vectors. The CPU version allows you to run this on machines without a GPU. It's useful for tasks like nearest neighbor search, which is common in recommendation systems and search engines.

2.Groq: Groq is a company developing AI hardware for high-performance machine learning workloads. It focuses on highly parallel processing and efficiency, commonly used in cloud and edge AI deployments.

3.Langchain: Langchain is a framework for developing applications that integrate with large language models (LLMs). It's designed to simplify workflows like prompt engineering, managing conversation flows, and integrating LLMs into applications.

4.Langchain Groq: This likely refers to an integration between the Langchain framework and Groq hardware to optimize LLM applications for high-performance AI hardware deployments.

5.PyPDF2: PyPDF2 is a Python library used for working with PDF files. You can use it to extract text, merge PDFs, rotate pages, and more. It's useful in data extraction and text processing tasks involving PDFs.

6.Langchain Google GenAI: This appears to be a Langchain module or integration with Google's Generative AI tools, allowing the use of Google’s AI capabilities (like large language models) in Langchain applications.

7.Streamlit: Streamlit is a Python library that helps you quickly build and share custom data applications. It’s widely used for creating web-based dashboards and interactive tools without needing extensive web development knowledge.

8.Langchain Community: This likely refers to the open-source or community-supported extensions of Langchain, where various contributions are made to enhance its functionality.

9.Python-dotenv: Python-dotenv is used to load environment variables from a .env file into your application, making it easier to manage sensitive information such as API keys, credentials, and configuration settings.

10.PyPDF: Another Python library for working with PDFs, similar to PyPDF2, but might have different features or support newer formats.

11.Google Cloud AI Platform (>=1.38): Google Cloud AI Platform provides a suite of machine learning tools hosted on the cloud, allowing you to build, train, and deploy models at scale. Version 1.38 or higher adds specific features or improvements, making it a critical tool for cloud-based ML deployments
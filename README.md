# Ragas Evaluation on Langflow

The repository implements the code for RAGAS metrics faithfulness, answer_relevancy, context_recall, and context_precision (https://docs.ragas.io/en/stable/index.html) on a RAG pipeline.

This is done by creating the custom component ragas_custom_component.json.

![image.png](README_files/langflowcode.png)


# Tutorial

Clone the repository


```python
git clone https://github.com/paulomuraroferreira/langflow_ragas.git
```

Install langflow and ragas:


```python
!pip install langflow run
!pip install ragas
```

On the terminal, execute


```python
langflow run
```

Upload the json RAG pipeline RAGAS metrics.json

![image.png](README_files/langflow_upload.png)

Copy the pdf documents to the pdf_documents folder,
or change the path in the Document Loader component:

![image.png](README_files/langflow1.png)

Enter your OpenAI API key on both Embeddings components,

![image.png](README_files/langflow2.png)

on the OpenAI models component,

![image-3.png](README_files/langflow3.png)

and on the Ragas custom component:

![image-4.png](README_files/langflow4.png)

Run the chunking pipeline by executing the ChromaDB component:

![Langflow Image](README_files/langflow9.png)

Enter the playground and ask questions:

![Langflow Image](README_files/langflow5.png)

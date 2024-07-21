# Ragas Evaluation on Langflow

Clone the repository


```python
git clone https://github.com/paulomuraroferreira/langflow_ragas.git
```


      Cell In[2], line 1
        git clone https://github.com/paulomuraroferreira/langflow_ragas.git
            ^
    SyntaxError: invalid syntax



Install langflow and ragas:


```python
!pip install langflow run
!pip install ragas
```

On the terminal, execute


```python
langflow run
```

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

Enter the playground:

![Langflow Image](README_files/langflow5.png)

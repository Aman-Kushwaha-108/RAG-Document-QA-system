# AI PDF QUESTION ANSWERING SYSTEM (RAG)  

### I've designed a RAG system in which we can upload the pdf and ask questions from it.It combines the Faiss and transformer based system to answer the questions.

## FEATURES OF THIS SYSTEM  
1-> Embedding generation using SentenceTransformer  
2-> Faiss-based vector similarity search  
3-> multi-stage retrieval(re-ranking)
4-> Logging system 




## Working  
1-> First it converts PDF to text   
2-> Then the Text is divided into chunks  
3-> Now each of the chunks will get converted into vector embeddings  
4-> FAISS is used after that to find the similar chunks   
5-> Now the model with generate andwers from the context  



## How to run it in your own system  
1-> Open the Google Colab or any IDE of your choice  
2-> install all the required libraries  
3-> Run all the cells  
4-> Upload a clean pdf file  
5-> Ask the question 



## Some Notes  
1-> Try to upload clean PDFs for best results.  
2->This is basic prototype of RAG system




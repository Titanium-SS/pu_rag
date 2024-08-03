# RAG App |🦜🔗|🦙| 🤖
<hr>
<div align="center">
    <img src="icon.ico" height=300> 
    <p>RAG Application in Python (Local and Online)</p>
</div>

<hr>

## Language Used: 
<div align="center">
<img src="readme/python.png" height=70 alt="Python">
</div>

<hr>

## Libraries Used:
<div align="center">
    <img src="readme/langchain.png" height=70 alt="Langchain"> 
    <img src="readme/pypdf.webp" height=70 alt="pypdf">
    <img src="readme/chromadb.png" height=70 alt="chromadb">
</div>


<hr>

## About:
This repo consists of Python Scripts for a simple RAG (Retrieval Augmented Generation) Application using Ollama🦙 and Langchain🦜🔗 that can be used both locally or using Google Gemini API key.

You can get your Google Gemini API key from <a href="https://aistudio.google.com/app/apikey">here</a>. 
 


<hr>

## Use Application:

Download and install <a herf="https://ollama.com/">Ollama</a>  on your device. 

and for necessary Python Libraries, simply run:

```
pip install -r requirements.txt
```

Pull necessary models (for embedding & text generation):

```
ollama pull <model_name>
```

used in this repo:

```
ollama pull nomic-embed-text
ollama pull phi3:3.8b-mini-4k-instruct-q4_K_M
```

Start a local server:

```
ollama serve
```


<hr>

## Run Application:

> Put your files (.pdf format) in the `data` folder.

> Run `python reload_db.py` for chunking and storing data in vector database.

> Once finished, make sure that ollama server is running and then you can start querying your database.

> Use the command `python query_local.py your_question` while using local LLM.

> Use the command `python query_api.py your_question` while using Google Gemini API.


<hr>

<u>Still under development</u>


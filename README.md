A locally hosted LLM Chatbot powered by Llama3, ChromaDB and SentenceTransformers. Takes a Youtube URL as input and let's you converse with the contents of the video.

To run this jupyter notebook, make sure you have Ollama and Llama3 installed. In case you do not have Ollama/llama3 on your system, run
```
pip install ollama
```
```
ollama pull llama3
```

Serve Ollama locally by running:
```
ollama serve
```

In a new terminal, create a new python virtual env and install required packages.
```
pip install -r requirements.txt
```

Replace the URL in the notebook to any video you wish to chat with. Cheers!

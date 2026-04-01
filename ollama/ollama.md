Ollama: Ollama is tool that let us run LLM models in our local machine. In simple word a local server that runs AI models and provides an api to use them.

Run ollama in local machine using docker:

``docker run -d --name ollama -p 11434:11434 -v ollama:/root/.ollama ollama/ollama``

in simply run the AI server.

run gemma: 

``docker exec -it ollama ollama run gemma2:2b``

in simply, run the AI model in AI server

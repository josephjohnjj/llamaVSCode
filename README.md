# llamaVSCode
Using Llama to with VSCode

## Download and Install LLAMA

Download and install [Ollama](https://ollama.com/download). 

## CodeLLAMA

There are multiple LLM available for Ollama. In this case we will be using __*Codellama*__ which can use text prompts to generate and discuss code. Once Ollama is installed download  __*Codellama*__ model
```
ollama pull codellama
```

Recheck if the model is available locally

```
ollama list
```

run __*Codellama*__

```
ollama run codellama
```

test the model 

![run](figs/run.png)

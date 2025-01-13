# ollama

- [Github](https://github.com/ollama/ollama)

# Start

```bash
ollama run llama3.2
```

# Customize Prompt

```bash
ollama pull llama3.2

# wrtie ModelFile
ollama create modelname -f ./path/to/ModelFile
ollama run modelname
```

# Python

## make virtualenv

```bash
python3 -m venv example_venv_path
source example_venv_path/bin/activate

# deactivate
deactivate

# remove
rm -rf example_venv_path
```

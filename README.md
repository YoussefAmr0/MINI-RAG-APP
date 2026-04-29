# mini-rag

this is a minimal implentation of the RAG model for question answering.

## Requirments 

-python 3.8 or later 

### install python using Miniconda

1) download and install miniconda from here https://docs.anaconda.com/free/miniconda/#quick-command-line-install

2) create new environment using the following command:

```bash
$ conda create -n mini-rag python=3.8
```

2) activate new envirnment:

```bash
$ conda activate mini-rag
```

### (Optional) Setup you command line interface for better readability

```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```

### installation

### install required packages

```bash
$pip install -r requirements.txt
```

### setup the environment variables 

```bash
$ cp .env.example .env
```
set your environment variables in the `.env` file. like `OPENAI_API_KEY` value.
# Langchain Demo

[Reference tutorial](https://www.youtube.com/watch?v=8BV9TW490nQ)

[Find/Create your Anthropic API key](https://console.anthropic.com/settings/keys)

[Find/Create your OpenAI API key](https://platform.openai.com/api-keys)

## Installation
### Create virtual environment
- With Conda:

`conda create -n langchain_demo python=3.11`

`conda activate langchain_demo`

- or with venv:

`python -m venv venv`

`source venv/bin/activate`

### Load python requirements
`pip install -r requirements.txt`

### Load notebook interface from command line
`jupyter notebook`

### Load local docker infra (redis)
`docker compose --env-file .env up -d`

#### Teardown containers and volumes once complete
`docker compose --env-file .env down --volumes`
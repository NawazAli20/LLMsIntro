# Installations commands for a fresh repo
create a project directory and issue the following commands in the project directory:

uv init
uv venv  

source .venv/bin/activate (#activate .venv)

### then install all the dependecies

uv add langchain

uv add langchain-openai 

#### or if you have listed all the required packages in the requirements.txt, issue: 

uv add -r requirements.txt


# Installations commands for a cloned repo
if you have .toml and/or .lock file just issue

uv sync 
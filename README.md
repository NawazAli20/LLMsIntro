# Installations commands 

Resource Links: 

- [UV github repo](https://github.com/astral-sh/uv)
- [langchain docs]()
- [Groq API Key](https://console.groq.com/keys)
- [OpenAI API Key](https://platform.openai.com/api-keys)

## Install uv On macOS and Linux.
curl -LsSf https://astral.sh/uv/install.sh | sh

## Install uv On Windows.
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

# for a fresh repo
### create a project directory and issue the following commands in the project directory:

uv init

uv venv  

source .venv/bin/activate (#activate .venv)

### then install all the dependecies

uv add *packagename*

Examples: 

uv add langchain

uv add langchain-openai 

uv add langchain-groq 

uv add ipykernel

uv add python-dotenv

#### or if you have listed all the required packages in the requirements.txt, issue: 

uv add -r requirements.txt


# Installations for a cloned repo

git clone https://github.com/NawazAli20/LLMsIntro

if you have .toml and/or .lock file just issue

uv sync 

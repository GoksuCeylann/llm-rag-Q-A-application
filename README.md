# LLM Q&A Application

## Setup

1. Create a virtual environment and install the libraries using the commands below:

I commented out the last line in the requirements.txt file. First, install the requirements this way, and then remove the comment symbol and install again. Otherwise you will get an error.

```bash
$ python3 -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```

2. If you are using the API (GPT):

Fill in the value in the .env file with your own API key:

```bash
OPENAI_API_KEY = [ENTER YOUR OPENAI API KEY HERE]
```

For local models, you can use Ollama. Here, I used llama3:8b.

3. Place the PDFs you will use inside the project folder. Then, you can run local.ipynb step by step. (Don't forget to add the paths.)

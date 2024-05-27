# Chat with Document
This repository contains code for interacting with a document using a combination of language models and retrieval techniques. It allows you to query information from a text document and receive relevant answers.

## Prerequisites
1. Install Python (Python 3.8 is recommended).
2. Create a virtual environment to manage dependencies by running 
	```sh
	python3 -m venv .venv
	```
3. Activate the virtual enviroment
	```sh
	.\.venv\Scripts\activate
	```
4. Install the required packages by running:
	```sh
	pip install -r requirements.txt
	```

5. Create an `.env` file and add the following variable:
	```
	OPENAI_API_KEY=<your_openai_api_key>
	```
	Replace `<your_openai_api_key>` with your actual OpenAI API key.
6. Run the Jupyter Notebook: To test the functionality, open the `chat_with_doc.ipynb` file and start running the code. You can also use your own text files for experimentation.

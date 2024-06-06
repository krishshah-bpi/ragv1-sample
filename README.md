# Rag Model Sample

## How to run this model

## Step 1

Download the requirements for the project using `pip install -r requirement.txt`

Also download Ollama from its website: https://ollama.com/

## Step 2

Load the data you want to use. You can upload PDFs in the data folder

## Step 3

Populate the Chroma database by running `python populate_database.py`. This will take all the data you have in your data folder, extract the texts, split up the texts for embedding, embed the text, and send it to the ChromaDB. 

## Step 4

Run `python query_data.py "{Whatever you want to put}"`. This will run the Llama model and generate the answer to your query.

## Step 5

You can optionally run unit tests if you want by editing and running `test_rag.py`

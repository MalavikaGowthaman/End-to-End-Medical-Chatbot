# End-to-End-Medical-Chatbot-Using-GenAI


Developed an Medical chatbot to make interact with user for the query based on disease, diagnosis, and treatment. 

# Tech used here:

- Python
- Pinecone VectorDB
- Huggingface embeddings
- Open AI LLM Model
- flask


# Steps followed here:

### Step 1

Create github repository and clone it using the following command

```bash
git clone https://github.com/MalavikaGowthaman/End-to-End-Medical-Chatbot.git
```

### Step 2 

Create a virtual environment in code editor

```bash
conda create -n medicalchatbot python=3.10 -y
```

### Step 3(Optional)

Create a project template(for folder and file creation) : template.py

```bash
python template.py
```

### Step 4 

Create .env file and add the API key's: 

PINECONE_API_KEY ='***********'

OPENAI_API_KEY = "*************"

### Step 5

Create requirements.txt file  add the required packages and library as needed.

Create a setup.py file. 

Run the following command to install packages

```bash
pip install -r requirements.txt
```

### Step 6 

Collect the necessary data. Here Medical book pdf is used to train the model.

### Step 7(Optional)

Create a notebook experiment for an step by step approach and understanding.

### Step 8 

Convert the notebook experiment to modular coding

- Create helper.py (for storing the functions of data loading, extract text and chunking)
- Create prompt.py (for prompt)
- Create store_index.py (for storing the embeddings download and vector database work)

### Step 9

Run the store_index.py

```bash
python store_index.py
```

Once the vector created develope an user app.

### Step 10

Create an app.py to develope an user friendly application using flask.






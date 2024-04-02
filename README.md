# Healthcare_chatbot
Streamlit HealthCare Chatbot with Llama 2&amp; Langchain on CPU Machine with MEMORY. [OPEN_SOURCE]


# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/siddhantsharma97/Healthcare_chatbot.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n chatbot python=3.8 -y
```

```bash
conda activate chatbot
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 03- Place your Huggingface API key in the .env file

```bash
HUGGINGFACEHUB_API_TOKEN="your_api_key"
```

### STEP 04- Run the application

```bash
streamlit run app.py
```

### Download the quantize model from the link provided in model folder & keep the model in the model directory:

```ini
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```
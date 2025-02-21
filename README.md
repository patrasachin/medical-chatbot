# Medical Chatbot

This project is a medical chatbot application built using langchain and Huggingface Inference API. Follow the steps below to set up the development environment and run the application.

## Prerequisites

- Anaconda or Miniconda installed
- Python 3.11
- Huggingface account and access token

## Setup Instructions

### 1. Create a Virtual Environment

First, create a virtual environment using conda with Python 3.11:

```bash
conda create --name myenv python=3.11
```

Activate the virtual environment:

```bash
conda activate myenv
```

### 2. Install Required Packages

Install the necessary packages using pip:

```bash
pip install -r requirements.txt
```

### 3. Set Huggingface Access Token

Create a `.env` file in the root directory of the project and add your Huggingface access token:

```plaintext
HF_TOKEN="your_access_token_here"
```
### 4. Run These Files 

```bash
python 1.create_memory_for_llm.py
```

```bash
python 2.connect_memory_with_llm.py
```


### 5. Run the Streamlit Application

Finally, run the Streamlit application:

```bash
streamlit run 3.medibot.py
```

This will start the Streamlit server and open the application in your default web browser.

## Additional Information

For more details on the workflow of the application, refer to the `Architecture.png` file.
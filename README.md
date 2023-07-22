# GPT-2-Chatbot-Inference-Script

The GPT-2-Chatbot-Inference-Script is an example script that uses the Hugging Face Inference API to generate conversation-like responses using the GPT-2 model. The script demonstrates the use of various parameters such as top_p, top_k, and contrastive sampling to tweak the response generation.

## Features

- Powered by OpenAI's GPT-2 model.
- Demonstrates the usage of top_p, top_k, and contrastive sampling for response generation.
- Easily customizable.

## Installation and Setup

First, clone the repository on your local machine:

```
git clone https://github.com/yourusername/GPT-2-Chatbot-Inference-Script.git
cd GPT-2-Chatbot-Inference-Script
```

Ensure that you have the necessary Python packages installed by running:
```
pip install -r requirements.txt
```

## Usage
To use this script:

Set your Hugging Face API key as an environment variable. Replace your_key with your actual key:
```
export API_Token=your_key
```

Run the main Python script:
```
python main.py
```

The script will output conversation-like responses based on the input string and the parameters defined in the script.

# Google Colab Chatbots

> Helping young learners to experiment with and understand large language models (LLMs) through hands-on projects in Google Colab.

## Overview
These are chatbots I built on Google Colaboratory. Each project introduces young learners to generative AI and its underlying frameworks while providing a platform for personal exploration and learning.

### [colab_api_chatbot.ipynb](https://github.com/boysbytes/colab-chatbot/blob/main/colab_api_chatbot.ipynb)
This chatbot implementation uses the Google Gemini API. I see the potential for learners to use this as their personal (and personalized) chatbot that they can use to bounce ideas while they are learning a topic.

Unfortunately, the model is proprietary and there are API usage limits.

### [colab_qwen2.5_chatbot](https://github.com/boysbytes/colab-chatbot/blob/main/colab_qwen2_5_chatbot.ipynb)
I decided to use the open source qwen2.5 0.5B model for this chatbot. The model is stored on Google Drive for persistent storage.

I'm less confident with the stability and reliability of this implementation.

### [colab_rag_chatbot(]https://github.com/boysbytes/colab-chatbot/blob/main/colab_rag_chatbot.ipynb)
Implemented RAG with this chatbot and switched to the open source smollm2 model. 

## Get Started
1. Open a notebook from the links above.
2. Select Open in Colab.
    1. For the chatbot using Google Gemini, you will need to create your own API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
    2. For the chatbot using qwen2.5, make sure to mount your Google Drive when prompted. \
    You also need to make sure you have enough storage space in your Google Drive.
    3. For the RAG-enabled chatbot, in addition to allowing access to your Google Drive to store the smollm2 model, you will also need to create a `rag_data` folder and upload the document you want the model to use.
3. Run each code cell in sequence to launch the chatbot.

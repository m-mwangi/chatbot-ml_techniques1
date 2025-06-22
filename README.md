# Maternal Health Chatbot
This project builds a domain-specific maternal healthcare chatbot using a pre-trained Transformer model. The chatbot provides an interactive platform where women can ask questions and receive immediate, accurate responses on a variety of maternal health topics.

## About Dataset
The dataset is sourced from Hugging Face (nyarkssss/gh-maternal-1k), which contains 1034 rows of conversational data specific to maternal health. 
Each record consists of:
Input - a user query related to maternal health
Output - a suitable response from a medical or domain-relevant source
Context - additional background to inform the conversation
Domain - various sections related to maternal health topic in general
Instruction - this gives guidelines on how the question is to be answered
Prompt - structures how the question is to be asked

## Evaluation Metrics
Model performance was tracked using several metrics:
- BLEU: Measures n-gram overlap between predicted and reference responses.
- F1 Score: Computed at token level to evaluate precision and recall balance.
- Accuracy: Measures exact token matches.
- Perplexity: Indicates how confident the model is in its predictions.

My metrics were as follows:
- Loss: 0.36937
- Accuracy: 0.92111
- BLEU Score: 0.14352
- F1 Score: 0.92111
- Perplexity: 1.11375

## How to run the chatbot
Begin by running all the cells in the given notebook. 
In the notebooks, there is a section called Chatbot Testing which when run, will provide the CLI to ask the chatbot maternal health related questions and it will give a reponse.

## Demo Video
https://youtu.be/lx4Xjppg-38


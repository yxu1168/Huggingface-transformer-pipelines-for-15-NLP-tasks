# Huggingface-transformer-pipelines-for-15-NLP-tasks
This Notebook implemented pretrained transformer pipelines to 15 Natural Language Processing tasks. Framework uses Tensorflow except table question answering which is only available for PyTorch. HuggingFace Transformer pipelines provides the following tasks out of the box:

* Sentiment analysis: is a text positive or negative?
* Text generation (in English): provide a prompt and the model will generate what follows.
* Name entity recognition (NER): in an input sentence, label each word with the entity it represents (person, place, etc.)
* Question answering: provide the model with some context and a question, extract the answer from the context.
* Filling masked text: given a text with masked words (e.g., replaced by [MASK]), fill the blanks.
* Summarization: generate a summary of a long text.
* Translation: translate a text in another language.
* Feature extraction: return a tensor representation of the text.
* Text Classification.
* Token classification.
* Zero shot classification.
* Conversation. etc.

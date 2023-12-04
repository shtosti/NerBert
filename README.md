# NerBert
A tutorial for fine-tuning BERT base (Spanish) on Polyglot NER dataset.

# TODO:
We will implement a `named entity recognition` system in Spanish. Using HuggingFace’s BertForTokenClassification class, we will initialize it with a pretrained Hugging Face BERT-base Spanish-language model. The HuggingFace guide for fine-tuning
serves as a good starting point. Before passing the data to the model, we will need to encode it using a HuggingFace tokenizer. 
<br> We will use a tokenizer corresponding to our BERT model. When provided with the right arguments, the tokenizer can also pad and truncate
the input.

# Useful Resources:
* Dataset at Hugging Face: https://huggingface.co/datasets/polyglot_ner
* Polyglot documentation: https://polyglot.readthedocs.io/en/latest/NamedEntityRecognition.html
* Freezing embeddings: https://discuss.huggingface.co/t/how-to-freeze-some-layers-of-bertmodel/917

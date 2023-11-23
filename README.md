# FindTheMeaning
Find The Meaning  application identifies and provides the meaning of a word in a passage.

How it works?: The System is framed as a Question-answering system fine-tuned to identify the word. The dataset is prepared from news websites and labelling is done programmatically. Fine tuning is performed on the "distilbert-base-uncased" model from Hugging face. To determine the meaning of the identified word, an external API is utilized.

Tools used:

      1. Pandas

      2. Hugging face datasets and transformers

      3. Pytorch

      4. Gradio

      5. API: https://api.dictionaryapi.dev/api/v2/entries/en/<word>

Link: https://huggingface.co/spaces/AravindAG/FindTheMeaning

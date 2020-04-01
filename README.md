# Spooky Author Identification!

With this project, I advanced my data engineering skills and experimented with NLTK on text data found on Kaggle. Used Word Embeddings and Recurrent Neural Networks with Keras to build a Deep Learning model that would guess the author (out of 3 possibilities) of a sentence with an accuracy of 84%.

## About Author Identification
Author identification is the task of identifying the author of a given text from a set of suspects. The main concern of this task is to define an appropriate characterization of texts that captures the writing style of authors. The aim of this project is to build a Deep Learning Neural Network model capable of assigning a given text to its respective author among the ones given in the **"Spooky Author Identification"** <a href="https://www.kaggle.com/c/spooky-author-identification"> **Kaggle dataset.** </a>
The models were run on a GTX 1080 GPU.


## About the Dataset

The dataset contains text from works of fiction written by famous spooky authors: Edgar Allan Poe, Howard Phillips Lovecraft and Mary Shelley. The data was prepared by partitioning large texts into single or multiple sentences.

Each record consists of three attributes:

- `id:` unique identifier for each text
- `text:` text (sentences or paragraphs) written by one of the authors
- `author`: the author of the sentence (EAP: Edgar Allan Poe, HPL: Howard Phillips Lovecraft; MWS: Mary Wollstonecraft Shelley)

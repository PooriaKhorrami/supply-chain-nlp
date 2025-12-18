# Supply Chain NLP – Sequence Modeling Project

This project applies fundamental Natural Language Processing (NLP) techniques to
supply chain event data by modeling operational processes as sequences.

Supply chain logs are treated as sentences, allowing the model to learn typical
process flows and generate plausible future steps using probabilistic and neural
language models.

## Implemented Concepts
- Tokenization and vocabulary construction
- N-gram language modeling (trigram)
- Probabilistic sequence generation


## Motivation
Supply chains generate large volumes of semi-structured and unstructured data
(e.g., logs, emails, reports). NLP-based sequence modeling provides an interpretable
and data-efficient approach for understanding operational patterns, especially in
small-data settings.

## How to Run
The project is designed to run entirely in **Google Colab**.

1. Open the notebook:  
   `supply_chain_nlp_ngram.ipynb`
2. Run all cells sequentially.

## Limitations
This project focuses on descriptive and predictive modeling of process sequences.
It does not perform optimization or guarantee optimal decisions.

## Author
Hossein (Pooria) Khorrami Sarvestani

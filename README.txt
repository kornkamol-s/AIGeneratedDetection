---------------------------------------------------------
  Folder Structure
---------------------------------------------------------
AI-detection/
|-- Code/                           # Codes
|   |-- train.ipynb                    # EDA, Data preparation, Parameter Selection, and Model Training
|   |-- test.ipynb                     # Evaluate models performance, using test set (Baselines, Random Forest, LSTM)
|   |-- test-BERT.ipynb                # Evaluate models performance, using test set (BERT) (Due to different library's version)
|   |-- tools.ipynb                    # Libraries and functions
|-- Models/                         # Saved trained models
|-- Source/                         # Source dataset
|   |-- *.jsonl                        # Source files from HuggingFace
|   |-- glove.6B.100d.txt	       # Pre-trained GloVe word embeddings
|   |-- *.pkl                          # Preprocessed Test sets for models evaluation


The evaluation scripts, "test.ipynb" and "test-BERT.ipynb", assess the performance of various models. "test.ipynb" includes Random Forests and LSTMs, while "test-BERT.ipynb" evaluates BERT models. To evaluate the two best models, navigate to the DistilBERT and BERT-Medium sections in the "test-BERT.ipynb" file.

All codes are developed on Google Colab: https://drive.google.com/drive/folders/1dGn8VtG4usocZLm-0Ulr5hdNdjxG7XhZ
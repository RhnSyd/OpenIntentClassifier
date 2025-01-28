## OpenIntentClassifier
OpenIntentClassifier is a BERT-based model designed to handle open intent classification for a banking chatbot. It distinguishes between in-scope questions related to banking services and out-of-scope queries, ensuring your chatbot can provide accurate and reliable responses—or gracefully handle queries outside its domain.

Features
Open Intent Classification: Classifies user queries into predefined banking intents or flags them as out of scope.
BERT-based Retrieval-Augmented Generation (RAG): Uses BERT for understanding user queries and generating intent classifications.
Customizable Dataset: Trained using datasets like BANKING77 but adaptable to other datasets for specific use cases.
Out-of-Scope Detection: Provides a safe fallback for questions beyond the scope of the banking chatbot.

# Getting Started
Prerequisites
Python 3.8 or later
Jupyter Notebook
Key Python libraries 

# Usage
Training the Model
Prepare your dataset in a format similar to BANKING77.
Modify the data_loader section in the provided Jupyter Notebook to load your dataset.
Run the RAG_based_framework.ipynb file in Jupyter Notebook to train and evaluate the model.
Testing the Model
Use the test batch processing functionality within the notebook to evaluate model performance on test data.
The notebook includes visualization tools for performance metrics.

# AI-Interview-ML-and-NPL

This Python script demonstrates a simple AI interview simulation, where the program randomly selects a term from a provided dataset and prompts the user to describe it. The program then calculates the cosine similarity between the user's input and the correct answer using the SentenceTransformer library.

## Installation

Make sure you have the required libraries installed:

```bash
pip install transformers
pip install sentence-transformers
pip install pandas

Usage
1. Clone the repository:
git clone https://github.com/https://github.com/osmarpessela98/AI-Interview-ML-and-NPL/edit/main.git

2. Install the necessary Python packages:
pip install -r requirements.txt

3. Run the script:
python ai_interview.py

Dependencies
transformers: Library by Hugging Face for state-of-the-art natural language processing.
sentence-transformers: Library for sentence embeddings using pre-trained models.

Data
The script uses a dataset in the form of an Excel file (AI interview sample dataset.xlsx) containing terms and their corresponding definitions. The data is loaded into a Pandas DataFrame for processing.

Model
The script utilizes the 'bert-base-nli-mean-tokens' model from the SentenceTransformer library to encode text into vectors.

How it Works
A random term is selected from the dataset, and the user is prompted to describe it.
The user's input and the correct answer are encoded into vectors using the SentenceTransformer model.
Cosine similarity is calculated between the two vectors to measure the similarity.
The correct answer, along with the calculated cosine similarity, is displayed.
Feel free to customize the dataset, model, or any other parameters to suit your specific use case.

Happy coding!

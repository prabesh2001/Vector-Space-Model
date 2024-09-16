

# Vector Space Model with TF-IDF for Document Retrieval

This repository implements the **Vector Space Model (VSM)** for document retrieval, using **TF-IDF (Term Frequency-Inverse Document Frequency)** to assess the relevance of documents based on a query. The model processes 10 text-based documents on topics such as AI, machine learning, and data analysis, and computes document-query similarities using **cosine similarity**.

Key features of the project include:
- **Text Preprocessing:** Tokenization, cleaning, and preparation of documents for analysis.
- **Term Frequency (TF) Calculation:** Measures how often a term appears in each document.
- **Inverse Document Frequency (IDF) Calculation:** Measures the importance of terms across all documents in the dataset.
- **TF-IDF Vectorization:** Combines TF and IDF to construct term vectors for documents and queries.
- **Cosine Similarity:** Computes the similarity between query and document vectors for relevance ranking.
- **Results Output:** Writes the ranked document-query results into a `.txt` file for further evaluation.

This project provides a practical example of how text can be transformed into numerical representations for search and information retrieval using the Vector Space Model and TF-IDF technique.

### Installation & Usage
1. Clone the repository
2. Install the required libraries from `requirements.txt`
3. Run the Python script to process the dataset and retrieve documents based on sample queries.

This model demonstrates the effectiveness of TF-IDF and VSM in retrieving relevant documents from a small dataset.

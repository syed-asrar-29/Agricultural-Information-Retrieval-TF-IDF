#  Agricultural Information Retrieval System Using TF-IDF and Cosine Similarity

## Overview

The Agricultural Information Retrieval System is a Natural Language Processing based project that retrieves and ranks agricultural documents according to their relevance to a user's search query.

The system uses TF-IDF and Cosine Similarity to calculate the similarity between the user's query and a collection of agricultural documents.

## Objectives

- Implement an Information Retrieval System using Python.
- Apply text preprocessing techniques.
- Calculate Term Frequency (TF).
- Calculate Document Frequency (DF).
- Calculate Inverse Document Frequency (IDF).
- Generate TF-IDF vectors.
- Calculate Cosine Similarity.
- Rank documents according to relevance.
- Retrieve the most relevant agricultural document.

## Technologies Used

- Python
- Google Colab
- Natural Language Processing
- NLTK
- NumPy
- Pandas
- Matplotlib

## Dataset

The system contains four agricultural documents:

| File | Topic |
|---|---|
| Text1.txt | Crop Cultivation and Soil Management |
| Text2.txt | Irrigation and Water Management |
| Text3.txt | Pest and Disease Management |
| Text4.txt | Organic Farming and Sustainable Agriculture |

## Methodology

The system follows the following process:

User Query
↓
Text Preprocessing
↓
Tokenization
↓
Stopword Removal
↓
Stemming
↓
Term Frequency
↓
Document Frequency
↓
Inverse Document Frequency
↓
TF-IDF
↓
Cosine Similarity
↓
Document Ranking
↓
Most Relevant Document

## TF-IDF

TF-IDF is calculated using:

TF-IDF(t,d) = TF(t,d) × IDF(t)

where:

TF represents Term Frequency and IDF represents Inverse Document Frequency.

## Cosine Similarity

Cosine Similarity is used to measure the similarity between the query vector and document vectors.

Cosine Similarity:

similarity(A,B) = (A · B) / (||A|| × ||B||)

A higher similarity score indicates that the document is more relevant to the query.

## Example Queries

### Query 1

soil nutrients crop growth fertilizer

Expected relevant topic:

Text1.txt - Crop Cultivation and Soil Management

### Query 2

drip irrigation water efficiency crops

Expected relevant topic:

Text2.txt - Irrigation and Water Management

### Query 3

insects pests crop disease prevention

Expected relevant topic:

Text3.txt - Pest and Disease Management

### Query 4

organic manure sustainable farming

Expected relevant topic:

Text4.txt - Organic Farming and Sustainable Agriculture

## Project Structure

Agricultural-Information-Retrieval-TF-IDF/
│
├── Agricultural_Information_Retrieval_TF_IDF.ipynb
├── Text1.txt
├── Text2.txt
├── Text3.txt
├── Text4.txt
└── README.md

## How to Run

1. Open the `.ipynb` file using Google Colab.
2. Run the cells from top to bottom.
3. Enter an agricultural search query.
4. The system calculates similarity scores.
5. Documents are ranked according to relevance.
6. The highest-ranked document is displayed as the most relevant result.

## Conclusion

This project demonstrates the application of Natural Language Processing and Information Retrieval techniques to agricultural information. TF-IDF represents the importance of terms, while Cosine Similarity determines the relevance between the user query and agricultural documents.

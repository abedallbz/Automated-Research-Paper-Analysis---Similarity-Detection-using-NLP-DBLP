The project performs the following full workflow:

Read PDF paper

Extract abstract + main text

Extract references list

Find every in-text citation

Save each citation’s context sentence

Search DBLP to identify the real external paper

Obtain external paper abstract

Compare: citation context vs external abstract

Compute similarity (TF-IDF + SIF)

Classify relevance of the reference
Technologies Used

Python

PyPDF2

NLTK

Scikit-learn

TF-IDF

Cosine similarity

Word embeddings + SIF

DBLP API search

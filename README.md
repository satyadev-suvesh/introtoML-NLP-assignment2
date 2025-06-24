# introtoML-NLP-assignment2 
## Summary

Manual TF‑IDF vs scikit‑learn TF‑IDF: Both compute the same concept, so their results are close to each other. Minor differences occur due to scikit‑learn’s smoothing or normalization conventions.
CountVectorizer vs TF‑IDF: CountVectorizer gives raw counts, so common words like “the” have high counts across documents. But, TF‑IDF drastically downweights common words (like “the”) because their IDF is low, making their final score almost negligible.
Common words appear in almost every document, so in raw counts, they have large score. But, in TF‑IDF they get scaled down (low IDF), making their score very less.

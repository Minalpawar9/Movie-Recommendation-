
# 🎥 Movie Recommendation System

This is a content-based movie recommendation system built using **Python** and **Scikit-learn** that suggests similar movies based on their genres, overview, keywords, cast, and crew.

## ✨ Project Highlights

- Combined multiple features like `genres`, `keywords`, `cast`, and `crew` into a single `context` column.
- Converted stringified JSON data (e.g., genres, cast) using custom `convert()` and `convert1()` functions.
- Used **TF-IDF Vectorizer** to transform text data into numerical vectors.
- Calculated **cosine similarity** to find movies with similar content.
- Created a `recommendationsystem()` function to recommend top 5 similar movies.
- Handled issues with missing data and indexing (like fixing “index out of bounds” errors).
- Tested the system with real movie titles like `'Spider-Man 3'` and `'Shanghai Calling'`.

## 🛠️ Tech Used

- Python
- Pandas
- Scikit-learn
- Ast (for parsing nested data)
- Jupyter Notebook

## 🧪 Example Usage

```python
recommendationsystem('Spider-Man 3')
```

Output:
```
Spider-Man 2  
Spider-Man  
The Amazing Spider-Man 2  
The Amazing Spider-Man  
Arachnophobia
```

---


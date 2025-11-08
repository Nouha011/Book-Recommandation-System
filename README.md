# Book Recommendation System

A simple content-based book recommender that suggests similar books based on genres, authors, and language.

## What it Does

Enter a book title and get 10 similar book recommendations! The system analyzes 15,000 books and finds the ones most similar to your input.

## How it Works

1. **Data Cleaning**: Removes duplicates, standardizes author names and genres 
2. **Vectorization**: Converts book features (title, author, language, genres) into one numerical vector 'Data'
3. **Similarity Calculation**: Uses cosine similarity to compare books
4. **Recommendation**: Returns top 10 most similar books

## Technologies Used

- Python 
- Pandas (data processing)
- Scikit-learn (CountVectorizer, cosine similarity)
- Jupyter Notebook

## Installation

1. Clone this repository:
```bash
git clone https://github.com/Nouha011/Book-Recommandation-System.git
cd Book-Recommandation-System
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook REcommander.ipynb
```

2. Run all cells in order

3. When prompted, enter a book title (lowercase, exact match):
```
Enter the book title you want recommendations for: gretel
```

4. Get your top 10 recommendations!

## Dataset

- **Original Dataset**: Too large for GitHub Source : [GoodReads Data Set](https://github.com/scostap/goodreads_bbe_dataset/blob/main/Best_Books_Ever_dataset/books_1.Best_Books_Ever.csv)
- **Cleaned Dataset**: `Cleaned_Books.csv` (15,000 books) - included in this repo
- The cleaned dataset contains: title, author, language, and genres

## Example Output
```
Enter the book title you want recommendations for: gretel

Top 10 recommendations for 'gretel':

Similar Book 1
Similar Book 2
...
```

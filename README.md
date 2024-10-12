# Book Recommendation System Using TF-IDF and Cosine Similarity

## Project Overview
This project is a book recommendation system that suggests similar books based on the content (title and author) of a selected book. It utilizes **TF-IDF vectorization** to convert text data into numerical form and computes **cosine similarity** to find similar books. Additionally, the project includes some exploratory data analysis (EDA) to visualize the distribution of average ratings and the number of books per author.

## Requirements
The project requires the following libraries to run:
- Python 3.10
- pandas
- numpy
- scikit-learn
- plotly
- csv file: `books_data.csv`

## Installation
Follow these steps to install the necessary libraries and run the project:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/book-recommendation-system.git

    cd book-recommendation-system
    ```

2. Install the required Python libraries:
    ```bash
    pip install pandas numpy scikit-learn plotly
    ```

3. Make sure the `books_data.csv` file is in the project directory.

## Code Structure

**1. Data Preprocessing:**

**2. Exploratory Data Analysis (EDA):**
   - Plot a histogram of the distribution of average book ratings.
   - Plot a bar chart showing the number of books by the top 10 authors.

**3. TF-IDF Vectorization:**
   - The book titles and authors are vectorized using **TF-IDF** (Term Frequency-Inverse Document Frequency) to convert the text into numerical values.

**4. Cosine Similarity Calculation:**
   - The similarity between books is calculated using **cosine similarity** on the TF-IDF matrix.

**5. Book Recommendation:**
   - A function `recommend_books(book_title)` is created that takes a book title as input and returns a list of 10 similar books based on cosine similarity scores.

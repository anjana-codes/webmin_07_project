# Final Project: Article Summarizer 

## Title: webmin-07-project

### Name: Anjana Dhakal, Date:12/04/2024

### Obejectives:

1. Extract text from the article's HTML.
2. Perform token-based and lemma-based sentiment analysis.
3. Generate histograms to visualize sentiment distributions.
4. Create summaries of the article and compare their polarity scores.
5. Reflect on the differences between the summaries and their quality.

##  Clone base repository
1. Create a new repo
1. Clone YOUR new repo down to your machine.

## Installation
1. Activate virtual environment
 ```
    python -m venv .venv
    venv\Scripts\activate
```
2. Install the required packages: 

```
python -m pip install beautifulsoup4
python -m pip install html5lib
python -m pip install requests
python -m pip install spacy
python -m pip install spacytextblob 
python -m pip install matplotlib

```
## Tools and Libraries
 The following tools and Python libraries were used:
  1. spaCy: For natural language processing, tokenization, and lemmatization.
  2. collections: For counting word frequencies.
  3. matplotlib: For visualizing sentence scores.
  4. requests: For fetching web pages.
  5. BeautifulSoup4: For extracting text from HTML.
 
 ## Key Task 

 1. Extraction of Article
 The HTML content of the article was extracted and saved to (garden_betty_no_dig_vegetable_garden.html).

 2. Token based analysis
 - Sentiment scores were calculated for sentences using token-based polarity.
 - A histogram visualized the distribution of token-based sentiment scores.
 - A token-based summary was created using a cutoff score.
 
 3. Lemma-Based Analysis
 - Sentiment scores were calculated using lemma-based polarity.
 - A histogram visualized the distribution of lemma-based sentiment scores.
 - A lemma-based summary was created using a cutoff score.

 4. Summary Comparison: 
   The polarity scores and number of sentences in both summaries were compared.

 5. Visualizations
 Histograms were generated to visualize sentiment score distributions.

## Export to HTML
Export Using Jupyter Menu
more options (...) tap near outline in the home page of Jupyter Notebook and export as HTML.

## Git add and commit

```
    git add .
    git commit -m " project completed"
    git push origin main

```

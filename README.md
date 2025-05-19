Automating Secondary Research – KPMG vs PwC Insights Analysis
This project was created as part of a written assignment to automate secondary research using AI and ML techniques. The goal was to extract insights from articles published by KPMG and PwC, analyze the content, and draw comparative insights between the two firms.

Objective
To scrape insights articles from KPMG and PwC websites, process and analyze the data using NLP techniques and clustering, and summarize the key findings through visualizations and comparisons.

Project Structure
Data Collection:
Scraped recent articles from both KPMG and PwC websites including:

Title

URL

Publication Date

Full Content

PDF Content (if available)

Preprocessing:

Removed stopwords, special characters, and unwanted terms

Normalized text for analysis

Industry Classification:

Used a rule-based + semantic similarity approach

Grouped articles by industry using SentenceTransformers

Topic Extraction:

Used TF-IDF and keyword frequency to extract top keywords

Identified common and unique themes for each firm

Clustering:

Used UMAP for dimensionality reduction

Applied HDBSCAN for unsupervised clustering of articles

Mapped clusters back to original articles for traceability

Visualization:

Bar charts for industry/topic distribution

Word clouds for key themes

Summary insights comparing both firms

📊 Key Findings
Both KPMG and PwC cover overlapping themes such as digital transformation and sustainability.

KPMG focuses more on ESG, technology, and transformation.

PwC emphasizes compliance, financial strategy, and market trends.

Visual comparisons and topic clusters reveal clear positioning and strategic focus areas of each firm.

🧰 Tech Stack & Libraries
pandas, numpy – Data handling

Selenium, BeautifulSoup – Web scraping

pdfplumber – PDF content extraction

scikit-learn, hdbscan, umap-learn – Clustering and modeling

sentence-transformers – Embedding and similarity

matplotlib, seaborn, wordcloud – Visualizations

📁 Files Included
kpmg_articles.csv, pwc_articles.csv: Raw scraped data

kpmg_articles_enriched.csv, pwc_articles_enriched.csv: Processed and classified articles

insights_analysis.ipynb: Complete notebook with code and visualizations

assignment_report.pdf: Final submission report with explanations and visuals

📎 Author
Pranati mishra

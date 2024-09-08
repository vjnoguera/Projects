
# Document Retrieval and Ranking System Using Embeddings and Indicator-Based Evaluation

This project analyzes scientific abstracts by utilizing a dataset of 10,000 publications. The primary aim is to process and extract meaningful insights from various metadata fields associated with these publications. The dataset includes detailed information such as the publication type, language, abstract content, and several unique identifiers for articles.

## Project Overview

The main goals of the project are to:
- Load and preprocess the dataset of scientific abstracts.
- Conduct data exploration and analysis to extract key metadata fields.
- Perform statistical analysis on fields such as publication types, languages, MeSH terms, and more.

**Please note this project has been developed for a company based in Spain, so some parts of the code might not be in english.**

## Data Structure

The dataset consists of several important columns:
- **PMID**: Unique identifier for each publication.
- **Authors**: List of authors for each paper.
- **Journal Title**: The name of the journal where the article was published.
- **Abstract**: The abstract of the publication.
- **Language**: The language in which the article was written.
- **Publication Type**: Indicates whether the article is a research paper, review, case report, etc.
- **MeSH Terms**: Medical Subject Headings (MeSH) used to categorize the articles.
- **Date of Publication**: The date the article was published.
- **NLM Unique ID**: Unique ID assigned by the National Library of Medicine.
- **Grant Number**: Information about funding received for the research.

## Key Processes

1. **Data Loading**: The dataset is loaded using `pandas` and cleaned to handle missing or incomplete values.
2. **Descriptive Statistics**: Provides an overview of the dataset with focus on key fields, such as the number of publications per language or the frequency of different publication types.
3. **MeSH Term Analysis**: Investigates the distribution of MeSH terms across the dataset to understand how articles are categorized.
4. **Date Analysis**: Examines trends over time, including the publication dates and revisions of the articles.

## Dependencies

This project requires the following Python libraries:
- `pandas` (for data manipulation)
- `numpy` (for numerical operations)

## How to Run

1. Ensure that you have the necessary dependencies installed by running:
    ```bash
    pip install pandas numpy
    ```
2. Open the Jupyter Notebook and run the cells to load and analyze the dataset.

## Data Insights

- **Language Distribution**: The dataset contains articles in multiple languages, with the majority in English.
- **Publication Types**: Research articles dominate the dataset, but there are also reviews, case reports, and editorials.
- **Date of Publication**: The data includes both historical and recent publications, providing a longitudinal view of the field.

## Future Improvements

Future work could include:
- Expanding the analysis to include deeper exploration of abstract content through natural language processing (NLP).
- Adding visualizations to better represent trends and insights from the data.
- Further cleaning and normalization of fields like authorship and grant numbers.

## License

This project is provided for educational purposes and does not include the original dataset. Please ensure you have appropriate permissions to use the data.


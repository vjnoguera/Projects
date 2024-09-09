# Repository Overview

This repository contains multiple projects related to data analysis and document ranking systems using various indicators and embedding techniques.

---

## 1. **EDA of Indicator Analysis (EDA)**

This project performs a detailed **Exploratory Data Analysis (EDA)** of bibliometric indicators for academic journals using the **Scimago Journal & Country Rank 2023** dataset. The analysis evaluates the quality and impact of journals based on metrics like SJR (Scimago Journal Rank), H-Index, citations per document, and more.

### Key Features:
- **Data Preprocessing**: Clean and prepare bibliometric data for analysis.
- **Visualization**: Generate visualizations such as bar charts, line graphs, and word clouds to display key trends.
- **Journal Comparison**: Filter and compare top academic journals by indicators such as country, quartile, and study field.
- **Insight Extraction**: Identify relationships between different indicators, such as SJR, H-Index, and citation counts.

### Technologies Used:
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly` for data analysis and visualization.
- `nltk`, `wordcloud` for text analysis.

### How to Run:
1. Clone this repository:
   ```bash
   git clone https://github.com/usuario/repo-analisis-indicadores.git
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
3. Open the Jupyter notebook:

    jupyter notebook "Análisis de indicadores.ipynb


## 2. **Document Retrieval and Ranking System Using Embeddings (DocRanker)**

This project focuses on analyzing scientific abstracts and recommending the most relevant documents based on **embedding techniques** and **indicator-based evaluations**. The system processes a dataset of 10,000 scientific publications and provides a ranking mechanism to compare and sort these documents based on their relevance and performance indicators.

### Key Features:
- **Embedding-based Retrieval**: Recommend documents related to a given input text using embedding models.
- **Metadata Analysis**: Analyze key fields like publication type, language, MeSH terms, and publication dates.
- **Ranking**: Compare retrieved documents using multiple indicators and present results in a ranked order.

### Technologies Used:
- `pandas` and `numpy` for data manipulation and numerical operations.
  
### How to Run:
1. Install the necessary dependencies:
   ```bash
   pip install pandas numpy
2. Open the Jupyter notebook to load and analyze the dataset.

## **3. ChatBot with Cohere Model**

This project is a Python web application built using the Flask framework, designed to interact with a MongoDB database. It allows retrieving data from a MongoDB collection, processing it using Pandas, and rendering a web interface.

### Features

- **Flask**: Serves the web interface and handles routing.
- **MongoDB Integration**: Connects to MongoDB to retrieve and process data.
- **Pandas**: Used for processing and handling data retrieved from the MongoDB collection.
- **Cohere API**: (If applicable) for natural language processing or other AI functionalities.
- **Cross-Origin Resource Sharing (CORS)**: Enabled to allow cross-origin requests.

### Prerequisites

- Python 3.x
- Flask
- MongoDB (either a local instance or MongoDB Atlas)
- Cohere API key (if using Cohere functionalities)

### Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <project-directory>

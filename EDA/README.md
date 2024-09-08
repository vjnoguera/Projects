# EDA of Indicator Analysis

This project performs a detailed analysis of bibliometric indicators of academic journals using the Scimago Journal & Country Rank 2023 dataset. The analysis focuses on metrics such as SJR (Scimago Journal Rank), H-Index, citations per document, and other key factors that allow evaluating the quality and impact of the journals.

This study is part of the development of a search tool to analyze scientific publications in databases and to classify and display the most relevant publications based on the search parameters entered.

About 20,000 publication records have been used, including SJR and H-index indicators as well as other attributes of each paper, such as its country of origin, the quartile to which it belongs, or the field of study.

## Project Content
The analysis includes:

Loading and preprocessing bibliometric data.
Visualization of key indicators.
Filtering and comparison of top academic journals by category.
Exploratory analysis and generation of graphs based on categories.
Technologies Used
Python: Main language for the analysis.
Libraries:
pandas: For data manipulation and analysis.
numpy: For advanced numerical calculations.
matplotlib and seaborn: For data visualization.
plotly: For interactive visualizations.
nltk: For text processing and frequency analysis.
wordcloud: For generating word clouds.
Results Obtained
The main charts used were bar charts, though alternatives such as line graphs and word clouds were needed. Some examples:

## Indicator magnitude assessment:

![imagen](./Gráficas/Magnitud%20SJR%20y%20H%20index.png)

Cross-referencing data between publishing countries and best index averages:

![imagen](./Gráficas/Indices%20por%20país.png)

Most used words in the analyzed titles:

![imagen](./Gráficas/Wordcloud.png)


## Conclusions
In conclusion, the study has highlighted important aspects to consider when evaluating a scientific publication in case its evaluation indices are unknown. This is highly useful for the second part of the project, which is yet to be carried out.

Based on the results obtained during the study, for publications that do not have an SJR or H-index, alternative aspects could be considered, in order of importance:

The quartile it belongs to, with Q1 being the priority.
The number of citations the publication has, as there is a relationship with SJR and H-index.
The country of origin, prioritizing those from the USA, UK, or Netherlands.
The publisher, mainly “Nature Search,” “Massachusetts Medical Society,” and “The Endocrine Society.”
Key Files
Análisis de indicadores.ipynb: Jupyter Notebook containing the full analysis.
scimagojr 2023_1.csv: CSV file with bibliometric data from the journals.

## How to Run the Project
Clone this repository:
   ```bash
   git clone https://github.com/usuario/repo-analisis-indicadores.git
   ```

## Install the required dependencies:

pip install -r requirements.txt

## Open the notebook with Jupyter:

jupyter notebook "Análisis de indicadores.ipynb"

## Contributions
Contributions to this project are welcome. If you have any improvements or suggestions, feel free to submit a pull request or open an issue.


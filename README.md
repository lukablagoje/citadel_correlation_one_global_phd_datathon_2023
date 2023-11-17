# Citadel-Correlation One Global PhD Datathon
This was a highly selective, individual competition, during which I tackled a confidential problem statement and documented my findings in a detailed [report](https://github.com/lukablagoje/datathon-report.pdf). Note that the main findings are in the report itself and the code is considered only as supplementary material.

For more details about the competition, check out this link:
- [Citadel Datathons](https://www.citadel.com/careers/students/datathons/)
# Research Overview
This research delved into the textual characteristics of clickbait, focusing on how they impact user engagement. Utilizing Natural Language Processing (NLP) techniques, I analyzed sentiments, emotions, and topics present in clickbait articles. My analysis involved a statistical evaluation and ranking of these factors in terms of their effect on user interaction, supplemented by the development of two null models to validate the reliability of this ranking. My methodological approach is encapsulated in the Clickbait Defender product concept:

![image](https://github.com/lukablagoje/citadel_phd_datathon_2023/assets/52599010/337c232f-a1b0-4ca9-a812-05702cd8a752)

# Technical Overview
My technical work on this project is divided into four main parts:

1. **Google Analytics Analysis**: Leveraging Google Analytics, I extracted and analyzed user engagement metrics. This involved studying user behavior patterns, click-through rates, and other relevant metrics to understand how users interact with clickbait content. The notebook [`google_analytics_analysis.ipynb`](https://github.com/lukablagoje/google-analytics-analysis) details this process.

2. **Data Cleaning, Processing and Exploratory Data Analysis**: I refined the dataset used in the original study, focusing on cleaning, categorizing, and preparing the data for deeper analysis. The notebook [`data_cleaning_processing_eda.ipynb`](https://github.com/lukablagoje/data-cleaning-processing-eda) contains the entire process.

3. **NLP Classification**: Here, I developed algorithms for classifying the text of clickbait articles. This part involves sentiment analysis, emotion detection, and topic categorization, as seen in [`nlp_text_classyfing_algorithms.ipynb`](https://github.com/lukablagoje/nlp-text-classyfing-algorithms).

4. **Statistical Rank Analysis, Null Models and Insights**: This section involves applying statistical models to the processed data to glean insights into user engagement. The Jupyter notebook [`google_analytics_analysis.ipynb`](https://github.com/lukablagoje/google-analytics-analysis) outlines this analysis.

# Data
I cannot provide the processed datasets that we have obtained for the competition, but I provide its source, The Upworthy Research Archive:
[https://upworthy.natematias.com/](https://upworthy.natematias.com/)

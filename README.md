# Hello, World! I'm Vadim 👋

<img src="https://files.catbox.moe/l5xhjw.gif" alt="Keanu Reeves" width="800"/>

I'm a fourth-year **Software Engineering student at Saratov State University**, focused on machine learning, information retrieval, and time-series analysis.

My coursework explores text representations and efficient document retrieval, and my search engine brings these interests into a working application. For my undergraduate thesis, I'm studying how to detect changes in the relationships between signals in multivariate time series. I'm also exploring deep learning, LLMs, and NLP applications.

Alongside my studies, I help prepare lectures for the machine learning club at [Development Students Club](https://dsc.alivetech.org).

## Projects & research

### [Undergraduate thesis: changes in time-series dependencies](https://github.com/karas3vv/diploma)

**In progress · Fourth year**

Studying how to detect changes in relationships between channels of a multivariate time series—even when individual signals retain their usual behaviour.

- The planned approach represents channels as nodes in graphs of dependencies built over successive time windows.
- Exploring Pearson correlation and mutual information to capture linear and nonlinear relationships.
- Currently reviewing the literature and designing experiments to evaluate detection quality, delay, and false alarms.

### [Habr article search engine](https://github.com/karas3vv/ssu-search-engine)

A search engine for Habr articles with a web interface and API.

- Built a pipeline for collecting articles, cleaning text, splitting it into chunks, and indexing embeddings.
- Used **BGE-M3 and Qdrant** for semantic search, with a local **Tantivy** lexical search mode and an experimental hybrid mode.
- Added spelling suggestions and compared retrieval quality and latency to choose the default search method.

### [LSH for news document retrieval](https://github.com/karas3vv/coursepaper-3year)

**Third-year coursework**

Investigated the trade-off between retrieval speed and recall when searching for similar news documents.

- Implemented **locality-sensitive hashing with random hyperplanes** for TF-IDF document vectors.
- Compared approximate retrieval with exact cosine-similarity search.
- Examined how index parameters affect the number of candidates, search time, and recall.

### [Semantic distance between documents](https://github.com/karas3vv/coursepaper-2year)

**Second-year coursework**

Compared ways to represent documents and retrieve texts relevant to a user query.

- Implemented retrieval with **TF-IDF, Word2Vec, and MiniLM embeddings** using cosine similarity.
- Added text preprocessing, including lemmatisation and stop-word removal.
- Visualised results to explore how document representations affect retrieval.

## Additional work

**[Service listing retrieval — Avito test assignment](https://github.com/karas3vv/avito-service-candidates)**  
Combined TF-IDF and BM25 candidate retrieval with LightGBM ranking.
Achieved **Recall@50 of 0.924 on 400 locally held-out queries**.

## Teaching & community

I help prepare and write lectures for the machine learning club at [Development Students Club](https://dsc.alivetech.org). This is another way I engage with ML alongside coursework and coding: organising concepts into learning materials for other students.

## Tools I use

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-3776AB?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

| Area | Tools |
| --- | --- |
| Data & machine learning | NumPy, pandas, Matplotlib, scikit-learn, LightGBM |
| NLP & search | Hugging Face, TF-IDF, BM25, Qdrant, Tantivy |
| APIs & infrastructure | FastAPI, PostgreSQL, Docker |
| Technical writing | LaTeX, Typst |

## Currently exploring

- **NLP & LLMs:** sentiment analysis, text summarisation, and question answering.
- **Information retrieval:** text representations, semantic search, and ranking evaluation.
- **Time series:** changes in dependencies between signals, as part of my thesis.

## Beyond code

I also experiment with **3D modelling in Blender** — some of my work is collected in [blender-projects](https://github.com/karas3vv/blender-projects).

## Let's connect

Feel free to reach out about ML and NLP projects, learning materials, or collaboration.

[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=fff)](https://t.me/karas3vv)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=fff)](mailto:karasevvd@gmail.com)

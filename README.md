# knowledge-graphs-on-medical-data


This repository provides an implementation of a **Medical Knowledge Graph** derived from research papers, which includes entities such as authors, mutations, genes, diseases, and abstracts. The knowledge graph allows for insights into relationships and trends within the medical domain, leveraging **Natural Language Processing (NLP)** and **graph visualization** techniques.

---

## Project Overview

The dataset was manually created by collecting and structuring data into columns such as:
- **Research Papers**: Titles and abstracts.
- **Authors**: Collaborators for each research paper.
- **Mutations**: Genetic mutations mentioned in the papers.
- **Genes and Diseases**: Biological entities connected to mutations.

This project processes the dataset and visualizes relationships among these entities using a **knowledge graph**.

---

## Key Features

1. **Entity Extraction**:
   - Identifying key entities such as genes, diseases, mutations, and authors from abstracts using dependency parsing and custom NLP functions.

2. **Relation Extraction**:
   - Extracting semantic relationships between entities using pattern matching with **spaCy Matcher**.

3. **Knowledge Graph Construction**:
   - Visualizing relationships among entities using **NetworkX** and **Matplotlib**.
   - Supporting subgraph generation for specific targets (e.g., diseases).

---

## Libraries Used

- **Python**: Primary programming language.
- **Pandas**: For data manipulation and preprocessing.
- **NLTK**: For tokenization, lemmatization, and stopword removal.
- **spaCy**: For dependency parsing and relation extraction.
- **NetworkX**: For constructing and visualizing knowledge graphs.
- **Matplotlib**: For graph visualization.

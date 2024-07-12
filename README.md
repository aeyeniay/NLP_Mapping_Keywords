# NLP Mapping Keywords

This project explores the use of natural language processing (NLP) techniques to map text documents to sustainability ontologies and ontology population. The main objective is to extract keywords from PDF documents and match them with relevant ontology classes.

## Table of Contents
- [Introduction](#introduction)
- [ESG: Ontology for ESG Assessment](#esg-ontology-for-esg-assessment)
- [Ontology and Web Ontology Language](#ontology-and-web-ontology-language)
- [Tools](#tools)
- [Uploading an Ontology and Simple Examples](#uploading-an-ontology-and-simple-examples)
- [Creating a DataFrame for the Keywords](#creating-a-dataframe-for-the-keywords)
- [Similarity Measures](#similarity-measures)
- [Conclusion](#conclusion)
- [Appendix](#appendix)
- [License](#license)
- [Contact](#contact)

## Introduction
Natural Language Processing (NLP) is a crucial field in computer science that enables machines to understand and process human languages. This project focuses on extracting text from PDF documents, identifying keywords using algorithms like BERT and RAKE, and matching these keywords to ontology classes. This approach significantly aids in summarizing and categorizing large volumes of text efficiently.

## ESG: Ontology for ESG Assessment
ESG (Environmental, Social, and Governance) criteria are essential for assessing the sustainability and ethical impact of a company or investment. This section delves into the importance of ESG and its components:

- Environmental: Waste and pollution, resource depletion, greenhouse gas emission, deforestation, climate change.
- Social: Employee relations, working conditions, community engagement, health and safety.
- Governance: Tax strategy, executive remuneration, political lobbying, corruption, board diversity.

## Ontology and Web Ontology Language
Ontologies represent a formal structure of knowledge within a domain. The Web Ontology Language (OWL) facilitates the representation of rich and complex knowledge about things and the relationships between them. This section explains the fundamentals of ontology and OWL, along with their applications in this project.

## Tools
PDF Extraction

Using Python libraries like extract_text, text is extracted from PDF documents. The process includes:

- Data Pre-Processing: Cleaning and formatting raw text.
- Machine Learning Language Models:
  - BERT: Bidirectional Encoder Representations from Transformers.
    
Visualization

- Keyword Cloud: Visual representation of frequently used keywords.
- Top N-grams: Analysis of unigrams, bigrams, and trigrams using CountVectorizer.
## Uploading an Ontology and Simple Examples
This section demonstrates how to upload and interact with ontologies using the owlready2 library in Python. Simple examples illustrate checking ontology classes and searching for specific terms within them.

## Creating a DataFrame for the Keywords
Keywords are stored in a DataFrame to facilitate matching with ontology classes. This setup allows for the calculation of similarity matrices, providing a quick overview of the relationship between keywords and ontology classes.

## Similarity Measures
Different similarity measures are used to compare keywords with ontology classes:

- Structural Similarity Index (SSIM): A perception-based model examining structural information.
- Jaccard Similarity Index: Measures resemblance between two sets.
- Sequence Similarity: Uses alignment to assess similarity.
- Sentence Transformers Similarity: Converts texts into vectors for comparison.
## Conclusion
The project highlights the importance of NLP in summarizing and categorizing text. By extracting keywords and matching them with ontology classes, it simplifies the process of analyzing large volumes of text, making it easier to derive meaningful insights.

## Appendix
Code implementation for this project is available on [GitHub](https://github.com/aeyeniay/NLP_Mapping_Keywords) 

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
If you have any questions or suggestions, feel free to contact me at [aeyeniay@gmail.com].

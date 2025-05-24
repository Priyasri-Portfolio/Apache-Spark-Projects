# Apache-Spark-Project 
Overview:
This project applies PySpark for text processing and exploratory analysis on War and Peace by Leo Tolstoy, 
using a dataset sourced from Project Gutenberg. The analysis includes:

--Word Frequency Analysis (Identifying commonly used words)
--Graph-Based Relationships (Using Edge-Vertex Graphs for word connections)
--Exploratory Statistics (Word length distribution, filtering techniques)

Dataset Information:
-Book Title: War and Peace
-Author: Graf Leo Tolstoy
-Translators: Aylmer Maude & Louise Maude
-Release Date: April 1, 2001 (eBook #2600)
-Most Recent Update: June 14, 2022
-Language: English
-Source: Project Gutenberg
-Credits: An Anonymous Volunteer and David Widger

Tech Stack
*Apache Spark (PySpark)
*Databricks
*GraphFrames (Edge-Vertex Graph Modeling)
*Natural Language Processing (NLP) Techniques

Book Title: War and Peace
Author:Graf Leo Tolstoy
Translator: 
--Aylmer Maude 
--Louise Maude

Release date: April 1, 2001 [eBook #2600]Most recently updated: June 14, 2022

Data Preprocessing:
--Tokenization: Splitting text into words
--Filtering: Removing short words and common stopwords
--Case normalization: Converting words to lowercase

How to Run:
-Login to Databrick
-start the cluster
-install libraries- Maven->Spark packages->graphframes:graphframes:0.8.4-spark3.5-s_2.12->install now
-run the cells

Acknowledgments
This project uses content from Project Gutenberg under its public domain policy.
Special thanks to contributors Aylmer Maude, Louise Maude, and David Widger for their efforts in translation and digitization.

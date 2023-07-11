# Similarity Analysis Runtime Analysis

This repository contains a runtime analysis of different similarity measures for documents larger than 50 words. The analysis includes the runtime comparison of Jaccard similarity and Cosine similarity measures using different representations and techniques. The runtime analysis is performed on a local machine with the following specifications: MacBook Pro, 2.4 GHz 8-Core Intel Core i9, 32 GB 2667 MHz DDR4.

## Table of Contents

- [Introduction](#introduction)
- [Analysis Sections](#analysis-sections)
- [Results](#results)
- [Instructions](#instructions)
- [License](#license)

## Introduction

The introduction section provides an overview of the similarity analysis techniques used, including Jaccard similarity and Cosine similarity. It explains their definitions, applications, and importance in various fields such as data mining, machine learning, and natural language processing.

## Analysis Sections

The analysis is divided into several sections, each focusing on a specific aspect of similarity analysis for documents larger than 50 words. The sections covered in this repository are as follows:

1. Analysis of the runtime of Jaccard similarity measure for documents represented as bags of words.
2. Analysis of the runtime of Cosine similarity measure for documents represented as dense vectors without the use of np.dot().
3. Analysis of the runtime of Cosine similarity measure for documents represented as dense vectors with the use of np.dot().
4. Analysis of the runtime of Cosine similarity measure for documents represented as bags of words.
5. Analysis of the runtime of all-pairs comparisons for more than 10 documents using either Jaccard similarity, Cosine similarity without np.dot(), or Cosine similarity with np.dot().
6. Analysis of the runtime of all-pairs comparisons for more than 10 documents using a multiprocessing paradigm (MapReduce).

## Results

The results of each analysis section are presented in a clear and concise manner. Each section includes details about the experimental setup, the runtime measurements, and any insights or observations derived from the analysis. The runtime results are compared and discussed to understand the efficiency and effectiveness of different similarity measures.

## Instructions

To replicate the analysis or use the provided code, follow the instructions below:

1. Clone the repository: `git clone https://github.com/your-username/repository-name.git`
2. Install the required dependencies mentioned in the project's documentation.
3. Run the specific analysis section of interest by executing the corresponding code files.
4. Analyze the runtime results and compare the performance of different similarity measures.
5. Modify or extend the code as needed for your specific use case or experiment.

## License

The content of this repository is licensed under the [MIT License](LICENSE).

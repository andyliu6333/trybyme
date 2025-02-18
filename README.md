# Red Light Camera Annual Charges 304304

## Overview
This repository contains the analysis for a study investigating the impact of enforcement start times on regional fine trends using Bayesian hierarchical modeling. The project leverages red-light camera fine data across multiple years and regions, aiming to answer two key questions:
-  Are there significant differences in fine trends across regions?
-  Does enforcement start time influence the peak or change pattern of fines?

## File Structure
The repo is structured as:
- `data/raw_data` contains the raw data as obtained from Open Data Toronto. 
- `data/analysis_data` contains the cleaned dataset and long-format datasets that was constructed stored in parquet. 
- `model` contains fitted models.
- `others` contains relevant details about LLM chat interactions, sketches, graphs and datasheets.
- `paper` contains the files used to generate the paper, including the Quarto document and reference bibliography file, as well as the PDF of the paper.
- `scripts` contains the R scripts used to simulate, download, test, and clean data. Also, it contains the exploratory data analysis and model building.

## Statement on LLM usage
The code for simulating and testing datasets was adapted from code generated by ChatGPT, while the text sections of the paper, including the abstract, introduction, discussion, and other analyses, were refined with the assistance of translation software (DeepL) and grammar-checking software (Grammarly). The entire chat history is available in `others/llms/usage.txt`.

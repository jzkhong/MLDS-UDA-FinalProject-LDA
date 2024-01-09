# MLDS Unstructured Data Analysis Final Project

## Exploring Academic Research Trends in the United Kingdom: A Longitudinal Analysis of Doctoral Theses Metadata from 1900 to 2022

## Overview
This repository hosts the Jupyter notebook which performs a comprehensive analysis of the UK's Doctoral Thesis Metadata from EThOS. The analysis focuses on various aspects of the doctoral theses, including exploratory data analysis of the publication years, institutional distribution & keywords in titles, preprocessing of thesis title, TF-IDF analysis and topic modeling using LDA.

## Dataset
The dataset, `EThOS_data.csv`, comprises bibliographic metadata for all UK doctoral theses listed in EThOS. Sourced from the British Library, it provides insights into thesis titles, authors, universities, subjects, and years of publication.

### Data Description
- **Title**: Title of the thesis.
- **Institution**: University where the thesis was submitted.
- **Subject Discipline**: Subject area of the thesis.
- **Date**: Year of publication.

## Notebook
The `EThOS-Analysis.ipynb` notebook includes detailed analysis with sections such as:
- Data Load
- Exploratory Data Analysis
- Pre-processing Thesis Title
- TF-IDF Analysis
- Bigram Generation
- Latent Dirichlet Allocation (LDA)
- LDA Results

Visualisations exported from the notebook and used in the PDF report are stored in the results folder.

### Hardware/Software Used
- Machine: Analysis was conducted on an Apple MacBook Pro laptop with Sonoma 14.2.1 macOS
- Specifications: Apple M1 Pro Chip with 32 GB memory
- Runtime: The estimated runtime for the entire notebook is approximately 1 hour 26 minutes.
- Python version: 3.10.11

### Dependencies
To run this notebook, the following specific versions of Python libraries are required:
- numpy 1.26.1
- pandas 2.1.4
- matplotlib 3.8.0
- seaborn 0.13.0
- wordcloud 1.9.3
- nltk 3.8.1
- scikit-learn (sklearn) 1.3.2
- gensim 4.3.2
- pyLDAvis 3.4.1

These can be installed via pip using the command `pip install numpy==1.26.1 pandas==2.1.4 matplotlib==3.8.0 seaborn==0.13.0 wordcloud==1.9.3 nltk==3.8.1 scikit-learn==1.3.2 gensim==4.3.2 pyLDAvis==3.4.1`.

### Installation and Running the Notebook
1. **Clone the Repository**:
   - Use the following command to clone the GitHub repository:
     ```bash
     git clone https://github.com/jzkhong/Unstructure-Data-Analysis-Project.git
     ```
2. **Install Dependencies**:
   - Install the required Python libraries using pip:
     ```bash
     pip install numpy==1.26.1 pandas==2.1.4 matplotlib==3.8.0 seaborn==0.13.0 wordcloud==1.9.3 nltk==3.8.1 scikit-learn==1.3.2 gensim==4.3.2 pyLDAvis==3.4.1
     ```
3. **Launch Jupyter Notebook**:
   - Navigate to the repository directory in terminal (for Mac users) or PowerShell (for Windows users).
   - Launch Jupyter Notebook using:
     ```bash
     jupyter notebook
     ```
4. **Open and Run the Notebook**:
   - In Jupyter, open `EThOS-Analysis.ipynb`.
   - Run the cells sequentially.

## Contributing
Contributions are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

### Dataset License
The `EThOS_data.csv` dataset used in this project is sourced from the British Library Research Repository and is available under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). This permits sharing and adaptation, provided appropriate credit is given, and changes indicated.

### Code License
Currently, the code in this repository is not under any specific open-source license and is shared for educational and research purposes. Please feel free to use and modify the code, keeping in mind that it adheres to the terms of the dataset's license and attributing any use of the dataset to the British Library Research service.


## Acknowledgements
We thank the British Library for providing the EThOS dataset, enabling this extensive analysis.
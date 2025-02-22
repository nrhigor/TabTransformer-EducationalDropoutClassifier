# Electrical Engineering Course Dropout Analysis using TabTransformer
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/nrhigor/TabTransformer-EducationalDropoutClassifier/blob/master/README.en.md)
[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/nrhigor/TabTransformer-EducationalDropoutClassifier/blob/master/README.md)

This repository contains the code and data used in the Electrical Engineering Graduation Thesis (TCC) at CEFET-MG, which investigates dropout rates in Electrical Engineering courses in Brazil using a machine learning model based on *TabTransformer*.

## Project Description

The project aims to classify colleges based on student dropout rates. To achieve this, the *TabTransformer* architecture was used, which adapts the transformer attention mechanisms to handle tabular data.

The data used in this study was extracted from the Higher Education Census of INEP, covering the period from 2014 to 2023. With this approach, the aim was to understand patterns and risk factors influencing dropout rates in Electrical Engineering courses, contributing to the development of more effective student retention strategies.

## Technologies Used

- **Language**: Python 3.12
- **Main Libraries**:
  - `pandas` (data manipulation)
  - `numpy` (mathematical operations)
  - `tensorflow` and `keras` (TabTransformer implementation)
  - `matplotlib` and `seaborn` (data visualization)
  - `imbalanced-learn` (class balancing)
  - `scikit-learn` (evaluation metrics and clustering)

## Installation

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/nrhigor/TabTransformer-EducationalDropoutClassifier.git
   cd TabTransformer-EducationalDropoutClassifier
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Contact

Author: **Higor Nunes Resende**  
Advisors: **Everthon de Souza Oliveira** and **Giovani Guimarães Rodrigues**   
Institution: *Centro Federal de Educação Tecnológica de Minas Gerais (CEFET-MG)*  
Email: [nrhigor@gmail.com](mailto:nrhigor@gmail.com)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


<p align="center">
  <img src="https://img.shields.io/github/license/joelle-jnbaptiste/SchoolProject---Ecommerce-customer-segmentation?style=for-the-badge" />
  <img src="https://img.shields.io/badge/School%20Project-ML%20%26%20Data-blueviolet?style=for-the-badge" />
</p>

<h1 align="center">✨ Ecommerce Customer Segmentation ✨</h1>

<div align="center">
  <em>
     *Understanding customer behavior through transactional data*
  </em>
</br>

 <b>Customer segmentation project based on real e-commerce data, combining data preparation, SQL analysis, exploratory data analysis, and clustering foundations</b>
</br>
</br>
🗃️ **Dataset**  
 https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
  
</div>

---


<!-- TABLE OF CONTENTS -->
<details>
  <summary>🧭 Table of Contents</summary>
  <ol>
    <li><a href="#-built-with">Built With</a></li>
    <li><a href="#-about-the-project">About The Project</a></li>
    <li><a href="#-dataset">Dataset</a></li>
    <li><a href="#-analysis-workflow">Analysis Workflow</a></li>
    <li><a href="#-repository-structure">Repository Structure</a></li>
    <li><a href="#-getting-started">Getting Started</a></li>
    <li><a href="#-license">License</a></li>
    <li><a href="#-contact">Contact</a></li>
  </ol>
</details>

---
### ✨ Built With

[![Python][Python-shield]][Python-url]
[![Jupyter][Jupyter-shield]][Jupyter-url]
[![Pandas][Pandas-shield]][Pandas-url]
[![NumPy][NumPy-shield]][NumPy-url]
[![Matplotlib][Matplotlib-shield]][Matplotlib-url]
[![Seaborn][Seaborn-shield]][Seaborn-url]
[![SQL][SQL-shield]][SQL-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🎯 About The Project

This project focuses on **customer segmentation for an e-commerce platform**, using real transactional data from the Brazilian Olist marketplace.

The main objectives are to:

- Prepare and clean complex relational datasets
- Perform exploratory data analysis (EDA) to understand customer behavior
- Use SQL queries to answer business-oriented questions
- Build meaningful customer representations based on purchasing behavior

Key topics covered in this project include:

- Data cleaning and preprocessing
- Relational data exploration (orders, customers, items, reviews)
- Feature engineering for customer-level analysis
- Statistical analysis and visualization
- Foundations for clustering-based segmentation

The project is implemented entirely in **Jupyter Notebooks**, with a strong emphasis on **interpretation**, **business insight**, and **data reasoning**.

---

## 🗃️  Dataset

The dataset used in this project comes from the **Olist Brazilian E-commerce Dataset**, publicly available on Kaggle.

Source:  
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset includes:

- Orders and order items
- Customer and seller information
- Payments and reviews
- Product categories and timestamps

This dataset enables realistic **end-to-end customer analysis** in an e-commerce context.

---

## 🧠 Analysis Workflow

The notebooks follow a structured workflow:

1. **Data Understanding**
   - Dataset overview
   - Relational schema exploration

2. **Data Cleaning**
   - Handling missing and inconsistent values
   - Data normalization and formatting

3. **Exploratory Data Analysis (EDA)**
   - Order volume and temporal analysis
   - Customer purchasing behavior
   - Descriptive statistics and visual insights

4. **SQL-Based Analysis**
   - Business-driven queries
   - Customer-level aggregations

5. **Feature Construction**
   - Creation of customer-level features
   - Preparation for segmentation tasks

6. **Segmentation Foundations**
   - Data preparation for clustering
   - Analytical interpretation of potential segments

Visualizations and conclusions are embedded directly in the notebooks.

---

## 🗺️ Repository Structure

    SchoolProject---Ecommerce-customer-segmentation/
    ├── input/                     # Raw Olist datasets
    ├── clean/                     # Processed and cleaned datasets
    ├── notebooks/
    │   ├── JEANBAPTISTE_Joelle_1_notebook_exploration.ipynb
    │   ├── JEANBAPTISTE_Joelle_2_notebook_scripts_SQL.ipynb
    │   └── JEANBAPTISTE_Joelle_3_notebook_essais_segmentation.ipynb
    └── README.md

---

## ⚔️ Getting Started

This project is designed to be explored locally using **Jupyter Notebook**.

### Prerequisites

- Python 3.8+
- pip or conda
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:

       git clone https://github.com/joelle-jnbaptiste/SchoolProject---Ecommerce-customer-segmentation.git

2. Navigate to the project folder:

       cd SchoolProject---Ecommerce-customer-segmentation

3. Install dependencies:

       pip install -r requirements.txt

4. Launch Jupyter Notebook:

       jupyter notebook

---

## ✒️ License

This project is provided for educational purposes.  
The dataset is publicly available on Kaggle and subject to its original license.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 🕊️ Contact

Joëlle JEAN BAPTISTE  
LinkedIn: https://fr.linkedin.com/in/joëllejnbaptiste  

Project Link: https://github.com/joelle-jnbaptiste/SchoolProject---Ecommerce-customer-segmentation

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

[Python-shield]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[Jupyter-shield]: https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white
[Jupyter-url]: https://jupyter.org/
[Pandas-shield]: https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org/
[NumPy-shield]: https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white
[NumPy-url]: https://numpy.org/
[Matplotlib-shield]: https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge
[Matplotlib-url]: https://matplotlib.org/
[Seaborn-shield]: https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge
[Seaborn-url]: https://seaborn.pydata.org/
[SQL-shield]: https://img.shields.io/badge/SQL-336791?style=for-the-badge
[SQL-url]: https://en.wikipedia.org/wiki/SQL

# Applying the Apriori Algorithm - Online Retail

This project demonstrates the application of the Apriori algorithm on an online retail dataset to extract frequent item sets and identify association rules between items.

## Introduction
Apriori is a popular algorithm for extracting frequent item sets from a transactional database and for identifying association rules between items in the item sets. The algorithm is designed to operate on databases containing transactions (for example, items bought by customers in a store).

## Project Structure
The project is implemented in a Jupyter notebook and includes the following sections:
- Import libraries and load the data
- Data cleaning
- Split data into transactions done in different countries
- One-Hot encode the dataset
- Build the model
- Analyze the results

## Data
The dataset used in this project is the online retail dataset from Kaggle. It contains transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered, non-store online retail.

## Installation
To run this project, you need to have Python and the following libraries installed:
- numpy
- pandas
- mlxtend

You can install these libraries using pip:

pip install numpy pandas mlxtend

## Usage
### Running on Google Colab
1. Open the notebook in Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sujana-Mollick/Applying-the-Apriori-Algorithm---Online-Retail/blob/main/Apriori_algorithm_online_store_dataset.ipynb)

2. Run the cells in the notebook to see the results.

### Running Locally
1. Clone the repository:
git clone https://github.com/Sujana-Mollick/Applying-the-Apriori-Algorithm---Online-Retail.git
2. Navigate to the project directory:
cd Applying-the-Apriori-Algorithm---Online-Retail
3. Open the Jupyter notebook:
jupyter notebook Apriori_algorithm_online_store_dataset.ipynb
4. Run the cells in the notebook to see the results.

## Conclusion
The project concludes that certain items are often purchased together, such as boys' and girls' cutlery, making for a clever rule to bunch cutlery together when shopping as a parent.

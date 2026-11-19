\# Group 10 – Galamsey Detection Project



\## Project Overview



This project focuses on the application of Artificial Intelligence and Machine Learning techniques for detecting and analysing illegal mining activities (Galamsey) in Ghana.



Using satellite-derived spectral bands and environmental indices, the project explores how machine learning models can identify patterns associated with mining activities and distinguish them from other land-cover conditions.



\## Project Objectives



\- Analyse the Ghana mining training dataset.

\- Perform data cleaning and preprocessing.

\- Explore spectral bands and derived environmental indices.

\- Develop machine learning models for mining detection.

\- Evaluate model performance using appropriate classification metrics.

\- Investigate spatial validation to reduce spatial data leakage.

\- Assess the ability of trained models to generalise to previously unseen geographical locations.



\## Technologies Used



\- Python

\- Jupyter Notebook

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn



\## Project Structure



```text

Group10-Galamsey-Detection-Project/

│

├── Galamsey\_Detection\_Project10.ipynb

├── ghana\_mining\_s2\_training.csv

├── README.md

├── requirements.txt

├── .gitignore

│

└── results/

```



\## Installation and Setup



1\. Clone the repository.

2\. Create and activate a Python virtual environment.

3\. Install the required libraries using:



```bash

pip install -r requirements.txt

```



4\. Launch Jupyter Notebook:



```bash

jupyter notebook

```



5\. Open `Galamsey\_Detection\_Project10.ipynb` and execute the notebook cells.



\## Dataset



The project uses the Ghana mining training dataset named `ghana\_mining\_s2\_training.csv`.



\## Model Evaluation



The project considers classification metrics such as:



\- Accuracy

\- Precision

\- Recall

\- F1-score



Spatially separated validation is also considered to assess model generalisation and reduce the risk of spatial data leakage.



\## Contributors



Group 10 – Artificial Intelligence Project



\## Project Status



Under development.


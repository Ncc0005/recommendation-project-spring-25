# recommendation-project-spring-25
Final Project for Nicholas C. Spring 2025 semester
This project analyzes the purchasing behavior across customer types in a B2B context. It applies clustering and k-nearest neighbors to recommend additional items based on previous orders.
The data used in this project has been transformed for privacy.

## Structure
- `notebooks/Final Code and EDA.ipynb`: The notebook used for the project. It includes the data ingestion cleaning, the first EDA, the Second EDA, and the Clustering and KNN methods.
- `data/`: Folder contains the dataset note. I did not include the dataset as even though it is encoded, it is somewhat proprietary to be posted on a public GitHub; I do have permission to share it solely with my instructors, though.
- `requirements.txt`: Dependencies

## Setup
``` Bash
git clone https://github.com/Ncc0005/recomendation-project-spring-25.git
cd recommendation-project-spring-25

## Virtual env
python -m venv venv
source venv/bin/activate
## Dependencies
pip install -r requirements.txt
## Notebook
jupyter notebook notebooks/Final\ Code\ and\ EDA.ipynb


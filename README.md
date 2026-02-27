# F1 Exploratory Data Analysis (EDA)

**Author:** Brandon Knight

A Python-based exploratory data analysis project using a Formula 1 dataset. The goal is to practice and deepen my understanding of EDA techniques by asking meaningful questions about the data and uncovering insights through code and visualizations.

---

## Goal

Analyze an F1 dataset using Python to explore patterns, trends, and stories within the data — using this project as a hands-on learning experience with EDA.

---

## Process

1. **Load data into Kaggle notebook**
   > Working in a Kaggle notebook for quick and easy access to the dataset.

2. **Explore the data**
   - Review tables to understand structure and relationships
   - Create an ERD (Entity Relationship Diagram) to map out the data model

3. **Formulate questions**
   - Identify interesting questions the data can answer

4. **Inspect & clean the data**
   - Handle nulls, inconsistencies, and formatting issues
   - Load final cleaned tables into a GCP environment to leverage SQL if needed

5. **Answer questions with code**
   - Write Python (and SQL where applicable) to answer each question

6. **Visualize findings**
   - Add charts and graphs to illustrate key insights

7. **Document everything**
   - Keep thorough notes and commentary throughout the notebook

---

## Data Notes

### About the Dataset

#### Context
Formula One (also Formula 1 or F1, officially the FIA Formula One World Championship) is the highest class of single-seat auto racing, sanctioned by the Fédération Internationale de l'Automobile (FIA). It has been one of the premier forms of racing around the world since its inaugural season in 1950.

#### Content
The dataset spans from **1950 through the 2025 season** and consists of multiple tables covering:
- Constructors
- Race drivers
- Lap times
- Pit stops
- ...and more

#### Acknowledgements
- Data through **2024** sourced from [Ergast MRD API](http://ergast.com/mrd/), gathered and published to the public domain by **Chris Newell**.
- From **2025 onward**, data is refreshed after each Grand Prix weekend using the Ergast-compatible API provided by [api.jolpi.ca](https://api.jolpi.ca).

---

## Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn)
- Kaggle Notebooks
- Google Cloud Platform (BigQuery / GCP)
- SQL

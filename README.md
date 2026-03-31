![Netflix](https://img.shields.io/badge/Netflix-E50914?style=flat&logo=netflix&logoColor=white) ![python](https://img.shields.io/badge/-Jupyter%20Notebook-05122A?style=flat&logo=jupyter&logoColor=F37626) 

# 🍿NETFLIX TITLES ANALYSIS

*This project explores a Netflix CSV dataset using Python. The analysis will focus on movies, TV shows, genres, ratings, release years, and other key content trends.*

The dataset is included in this repository and will be analyzed using **Python libraries** such as **Pandas** and **Matplotlib**.

### Dataset Overview

*In this section, the dataset is loaded and reviewed to get a quick understanding of its structure before moving into the analysis.*

1. **Pandas** is imported to handle data loading, transformation, and analysis throughout the project. The dataset is loaded from the **CSV file** into a Pandas **DataFrame** for further exploration.

```python
import pandas as pd

df = pd.read_csv('netflix_titles.csv')
```

2. **The first five rows** are displayed to get an initial look at the dataset structure and content.

```python
df.head()
```

<img width="1387" height="450" alt="image" src="https://github.com/user-attachments/assets/d67f6da0-b174-42a6-a4a8-e66daff97336" />

3. **The last five rows** are displayed to verify how the dataset ends and confirm consistency across the file.

```python
df.tail()
```

<img width="1386" height="453" alt="image" src="https://github.com/user-attachments/assets/30f331e2-40fb-436a-a065-96c382ec12c9" />

4. **The shape** of the dataset is checked to identify the total number of rows and columns.

```python
df.shape #(rows, columns)
```

<img width="109" height="39" alt="image" src="https://github.com/user-attachments/assets/b1290b47-f4a9-4a41-90da-6822e281101b" />

5. **The column names** are reviewed to understand which variables are available for analysis.

```python
df.columns
```

<img width="1045" height="94" alt="image" src="https://github.com/user-attachments/assets/22886fc6-d8ab-4d07-abce-8d9adce1aad0" />

6. **The dataset structure** is inspected to review data types and identify missing values before starting the cleaning process.

```python
df.info()
```

<img width="490" height="414" alt="image" src="https://github.com/user-attachments/assets/b9970106-fdeb-4989-a86a-aa823cb6b2f4" />

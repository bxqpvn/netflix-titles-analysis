![Netflix](https://img.shields.io/badge/Netflix-E50914?style=flat&logo=netflix&logoColor=white) ![python](https://img.shields.io/badge/-Jupyter%20Notebook-05122A?style=flat&logo=jupyter&logoColor=F37626) 

# 🍿NETFLIX TITLES ANALYSIS

*This project explores a Netflix CSV dataset using Python. The analysis will focus on movies, TV shows, genres, ratings, release years, and other key content trends.*

The dataset is included in this repository and will be analyzed using **Python libraries** such as **Pandas** and **Matplotlib**.

### Dataset Overview

```python
import pandas as pd

df = pd.read_csv('netflix_titles.csv')
```

```python
df.head()
```

<img width="1387" height="450" alt="image" src="https://github.com/user-attachments/assets/d67f6da0-b174-42a6-a4a8-e66daff97336" />

```python
df.tail()
```

<img width="1386" height="453" alt="image" src="https://github.com/user-attachments/assets/30f331e2-40fb-436a-a065-96c382ec12c9" />

```python
df.shape #(rows, columns)
```

<img width="109" height="39" alt="image" src="https://github.com/user-attachments/assets/b1290b47-f4a9-4a41-90da-6822e281101b" />

```python
df.columns
```

<img width="1045" height="94" alt="image" src="https://github.com/user-attachments/assets/22886fc6-d8ab-4d07-abce-8d9adce1aad0" />

```python
df.info()
```

<img width="490" height="414" alt="image" src="https://github.com/user-attachments/assets/b9970106-fdeb-4989-a86a-aa823cb6b2f4" />

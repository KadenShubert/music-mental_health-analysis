# Music Mental Health EDA

People often use music to impact their moods and mental health awareness is more present than ever. The analysis of this dataset aims to identify patterns within the listening habits to gain insights into what makes listening habits have a positive versus negative impact for a given person, these insights could provide enough information for someone to identify how a change in their listening habits could positively impact their mental health.

## Solution
The goal of this project was to uncover the relationships in listening habits of a diverse group of individuals and how they report it impacts their mental health using [this Kaggle dataset](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results). EDA was performed on the dataset to uncover these relationships along with visualizations to support the findings. A Random Forest Classification model was trained using the cleaned and formatted data, using the features deemed to be most impactful from a feature importance analysis, along with the ability to input new data to predict if the provided personal features and listening habits will lead to improved mental health.

### Repo structure
- **Assignment_1_Kaden_Shubert.ipynb**: A Jupyter Notebook containing all data analysis, visualizations and model training. This notebook was developed use in Google Colab.
- **Music_MentalHealth_Data.csv**: Dataset from kaggle containing mental health information along with personal information from a survey spread through numerous online forums.

<h1 align="center">Air Traffic Clustering and Classification</h1>

---

# Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Project Structure](#project-structure)
- [Project Goals](#project-goals)
- [Key Insights](#key-insights)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)

# Project Overview

The **Air Traffic Clustering and Classification** project focuses on analyzing global air traffic data to uncover patterns, group similar traffic flows, and classify airport categories using machine learning techniques. The dataset includes various features such as geographic location, airport types, passenger and freight traffic, and regional attributes.

The main objectives of this project are:
- To perform clustering to group similar airports based on traffic and operational attributes.
- To develop a classification model that can predict airport categories based on the clustering performed before.
- To visualize the spatial distribution and statistical characteristics of air traffic around the world.

This project applies unsupervised and supervised learning techniques to support data-driven aviation planning and policy decisions.

# Data Source

The dataset used in this project is sourced from [Airline Traffic Passenger statistics Dataset](https://www.kaggle.com/datasets/thedevastator/airlines-traffic-passenger-statistics/data).

# Project Structure

```
├── [Clustering]_Submission_Akhir_BMLP_Rio_Octaviannus_Loka.ipynb   # clustering model
├── [Klasifikasi]_Submission_Akhir_BMLP_Rio_Octaviannus_Loka.ipynb  # classification model 
├── air_traffic_clustered.csv                                       # clustered dataset
├── Air_Traffic_Passenger_Statistics.csv                            # original dataset     
├── README.md                                                       # project documentation
└── requirements.txt                                                # project's depedencies
```

#  Project Goals

1. Perform **data preprocessing** and exploration from raw airport data.
2. Apply **clustering algorithms** such as K-Means to identify natural groupings of airports and check the silhouette score.
3. Train and evaluate **classification models** (KNN and SVM) to predict airport categories.
4. Visualize spatial and statistical results to communicate insights effectively.

#  Key Insights

Some of the key findings from the project include:

- Clustering revealed 3 distinct groupings based on passenger volume, geographical region, and airport function.
- The classification model achieved high accuracy in predicting airport types based on selected features.

# Tech Stack

<a href="https://www.python.org/"><img src="https://techstack-generator.vercel.app/python-icon.svg" alt="Python Icon" title="Python" width="65" height="65" /></a>
<a href="https://jupyter.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=jupyter" alt="Jupyter Notebook Icon" title="Jupyter Notebook" width="65" height="65" /></a>
<a href="https://pandas.pydata.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=pandas" alt="Pandas Icon" title="Pandas" width="65" height="65" /></a>
<a href="https://matplotlib.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=matplotlib" alt="Matplotlib" title="Matplotlib" width="65" height="65"/></a>
<a href="http://seaborn.pydata.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=seaborn" alt="Seaborn" title="Seaborn" width="65" height="65"/></a>
<a href="https://scikit-learn.org/stable/"><img src="https://go-skill-icons.vercel.app/api/icons?i=scikitlearn" alt="Scikit Learn" title="Scikit Learn" width="65" height="65"/></a>

# Installation

1. Clone this repository

   ```bash
   git clone https://github.com/RioOctaviannusLoka/Air-Traffic-Clustering-Classification.git
   ```

2. Install Python Virtual Environment Library

   ```bash
   pip install virtualenv
   ```

3. Create Python Virtual Environment

   Linux / Mac:

   ```bash
   python3 -m virtualenv venv
   ```

   Windows:

   ```bash
   python -m virtualenv venv
   ```

4. Activate the Environment

   Linux / Mac:

   ```bash
   source venv\bin\activate
   ```

   Windows:

   ```bash
   venv\Scripts\activate
   ```

5. Install all the requirements

   ```bash
   pip install -r requirements.txt
   ```

# Usage
1. Activate the Environment

   Linux / Mac:

   ```bash
   source venv\bin\activate
   ```

   Windows:

   ```bash
   venv\Scripts\activate
   ```

2. Open clustering notebook, then run each cell codes

3. Open classification notebook, then run each cell codes

4. Exit the Virtual Environment

   ```bash
   deactivate
   ```

---

Copyright &copy; 2025 - Rio Octaviannus Loka
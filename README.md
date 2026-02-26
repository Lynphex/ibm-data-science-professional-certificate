# IBM Data Science Professional Certificate - Capstone Project
## Predicting Successful Rocket Landings (SpaceX Falcon 9)

This repository contains the final Capstone Project and the complete set of notebooks developed for the **IBM Data Science Professional Certificate** via Coursera. 

### 🎯 Project Overview
The goal of this project is to predict if the first stage of a SpaceX Falcon 9 rocket will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. 

This project follows the **IBM Data Science Methodology**, covering everything from data collection to predictive modeling.

### 🛠️ Tech Stack & Tools
* **Language:** Python 3.x
* **Libraries:** Pandas, Numpy, Matplotlib, Seaborn, Folium (Maps), Plotly Dash (Dashboards), Scikit-learn (Machine Learning).
* **Tools:** Jupyter Notebooks, IBM Cloud, SQL, GitHub.

### 📋 Project Phases (Notebooks Included)
1.  **Data Collection:** Gathering data using the SpaceX API and Web Scraping from Wikipedia.
2.  **Data Wrangling:** Cleaning the data and performing feature engineering to prepare it for analysis.
3.  **Exploratory Data Analysis (EDA):** * Using **SQL** to perform queries and gain initial insights.
    * Using **Pandas/Matplotlib/Seaborn** to visualize relationships between variables (Payload, Orbit, Launch Site).
4.  **Interactive Visual Analytics:** * **Folium:** Creating maps to visualize launch site proximity to coastlines and railways.
    * **Plotly Dash:** Building an interactive dashboard for real-time data filtering.
5.  **Predictive Analysis (Machine Learning):** * Standardizing data and splitting it into Training/Test sets.
    * Training models: Logistic Regression, Support Vector Machine (SVM), Decision Tree, and K-Nearest Neighbors (KNN).
    * Optimizing hyperparameters using **GridSearchCV**.

### 📊 Key Findings
* The **Decision Tree** and **SVM** models provided the highest accuracy in predicting landing success.
* Success rates vary significantly depending on the launch site and orbit type.

---

### 💡 About This Certification
While I already hold a year-long **Master's/Bootcamp in Big Data, AI, and Machine Learning from KeepCoding Tech School**, I completed this IBM Professional Certificate to:
* Validate my skills under **IBM's industry-standard** methodology.
* Refresh and maintain my Python and SQL agility.
* Apply advanced visualization tools (Folium/Dash) to a real-world aerospace case study.

---
*Feel free to explore the notebooks! If you're interested in my profile as a Data Scientist, let's connect on [LinkedIn](www.linkedin.com/in/anelvalle).*

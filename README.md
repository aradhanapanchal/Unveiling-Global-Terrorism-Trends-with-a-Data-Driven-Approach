# 🧠 Unveiling Global Terrorism Trends with a Data-Driven Approach

## 📘 Introduction
Global terrorism is a major concern at the international level. Understanding its trends and patterns is important to develop effective anti-terrorism strategies.  
The **Global Terrorism Database™ (GTD)** is an open-source database that includes information on terrorist events around the world from **1970 through 2020**.

The GTD includes systematic data on domestic as well as transnational and international terrorist incidents that have occurred during this period and now includes **more than 200,000 cases**.  

For each GTD incident, information is available on:
- Date and location of the incident  
- Weapons used and nature of the target  
- Number of casualties  
- Group or individual responsible (when identifiable)  

The database is maintained by the **National Consortium for the Study of Terrorism and Responses to Terrorism (START)** at the **University of Maryland**.

---

## 🔑 Key Points of the Global Terrorism Database
- Contains information on **over 200,000 terrorist attacks**
- The most comprehensive **unclassified database** on terrorist attacks in the world
- Includes:
  - **88,000+ bombings**
  - **19,000+ assassinations**
  - **11,000+ kidnappings** since 1970
- Records **45+ variables** for each case; more recent incidents have **120+ variables**
- Over **4,000,000 news articles** and **25,000 news sources** reviewed to collect incident data (1998–2017)

---

## 🌍 What is the Global Terrorism Database?
The **GTD** is the most comprehensive open-source database on terrorist attacks globally, covering over **200,000 incidents** from 1970 through 2020.

Several research studies have analyzed trends and patterns in global terrorism using GTD data.  
These studies explore:
- Geographic distribution and temporal trends  
- Attack characteristics and evolving nature of terrorism  
- Predictive modeling of terrorism likelihood  

Some researchers have used **machine learning** and **predictive analytics** to forecast terrorist activities, employing models like:
- Logistic Regression  
- Random Forest  
- Support Vector Machines (SVM)

Such methods provide valuable insights into **risk assessment** and **preventive strategies**.

---

## 📊 Exploratory Data Analysis (EDA)
**Exploratory Data Analysis (EDA)** plays a crucial role in identifying patterns and trends in terrorism data over time.  

Through EDA, we can visualize:
- Geographic locations of incidents  
- Attack types and targets  
- Weapon usage patterns  
- Casualty trends  

EDA also supports **feature selection** and **data preparation**, enabling machine learning models to perform efficiently.

---

## 🧩 Approach

Predicting future trends and patterns of terrorist attacks based on historical data is challenging but feasible through **data science and machine learning** techniques.

Our project follows a structured **data-driven approach**:

 - We gather and preprocess extensive datasets from authoritative sources, ensuring accuracy and reliability in our analysis. Through exploratory data analysis techniques, These findings from analysis collectively contribute to a better understanding of the patterns, trends, and characteristics of global terrorism activities, which is important for devising effective counter-terrorism strategies and enhancing global security. By using this analysis, we have addressed the Data preparation part and Feature Engineering.
 - By identifying the most relevant features, we aimed to enhance the efficiency and interpretability of our models. For feature selection, we have used the SelectKBest from sklearn.feature_selection to select the top k features based on the chi-squared (chi2) statistical test.
 - By harnessing the predictive power of machine learning algorithms, we unlock the ability to forecast future trends in terrorism based on historical data. Through the implementation of Random Forest, Support Vector Machines, and Gradient Boosting models, we have developed predictive models to forecast future trends in terrorism.


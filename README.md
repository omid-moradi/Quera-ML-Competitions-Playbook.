# Quera Problem Solutions

This repository contains my solutions to various data science and machine learning problems from [Quera](https://quera.org/). Below is a list of the problems, each with a detailed description of the task.

---

## Important Note: Datasets

Please note that the datasets required to run these projects are **not** included in this repository due to their size and copyright. You can (and must) download the necessary data files directly from the official problem links provided below on the Quera website.

---

## Problem List

### 1. Saving Customers at "Ava Telecom"
* **Link:** [https://quera.org/problemset/307574](https://quera.org/problemset/307574)
* **Description:** This is a **classification** problem focused on predicting customer churn. "Ava Telecom" is experiencing increased customer loss after a new competitor entered the market. The goal is to build a model that predicts the probability of a customer churning. The model must use a combined dataset of classic customer data (like membership duration, contract type, monthly fees) and, crucially, the *text* from their support call transcripts.

### 2. Movement Status
* **Link:** [https://quera.org/problemset/254935](https://quera.org/problemset/254935)
* **Description:** This problem involves **Human Activity Recognition (HAR)**. We are given time-series data from motion sensors (accelerometers) placed on a person's right thigh and lower back. The task is to build a classification model that can predict the person's current physical activity (e.g., walking, running, standing, etc.) based on these sensor readings. The model is evaluated using the **Macro F1 Score**.

### 3. Successful Startup
* **Link:** [https://quera.org/problemset/254934](https://quera.org/problemset/254934)
* **Description:** A predictive **classification** task designed to help a new entrepreneur. The objective is to use a dataset of past startups (which includes both successful and failed ventures) to build a model. This model must predict the ultimate success or failure of a new startup based *only* on its performance data from its first few months of operation. The evaluation metric is the **F1 Score**.

### 4. How Much Per Night?
* **Link:** [https://quera.org/problemset/251283](https://quera.org/problemset/251283)
* **Description:** This is a classic **regression** problem for an accommodation booking website. The site needs a model to determine if newly listed properties are priced fairly. The goal is to build a model that accurately predicts the nightly rental price of a property based on its features (e.g., location, property type, size, amenities, number of rooms). The model's performance is measured by the **R2 Score**.

### 5. Criminology
* **Link:** [https://quera.org/problemset/251279](https://quera.org/problemset/251279)
* **Description:** A **multi-class classification** problem focused on public safety. We are given a large dataset of criminal incidents from Los Angeles. This data includes details like the date, time, location, victim demographics, and weapon used. The task is to develop a machine learning model that can predict the *type* of crime that occurred. Performance is evaluated using the **Macro F1 Score**.

### 6. Suspicious Noise
* **Link:** [https://quera.org/contest/assignments/84381/problems/308149](https://quera.org/contest/assignments/84381/problems/308149)
* **Description:** An **anomaly detection** problem using real-world data from industrial sensors. These sensors are prone to malfunctions or capturing noise. The objective is to build a model that can distinguish these abnormal (anomalous) data points from the normal sensor readings. This is critical for monitoring equipment health and preventing failures. The evaluation metric is the **F1 Score** for the anomalous class.

### 7. Sporting Director of "Azarakhsh"
* **Link:** [https://quera.org/contest/assignments/84381/problems/308143](https://quera.org/contest/assignments/84381/problems/308143)
* **Description:** A unique **recommendation system** problem with constraints. We are the sporting director of the 'Azarakhsh' football club and must find replacements for two key players who were sold. The challenge is to find a *pair* of new players using only **80% of the transfer fee** received. The recommendation must balance four key factors: **Profile Similarity** (technical skills), **Quality Maintenance** (team's overall rating), **Youth Factor** (preferring younger, high-potential players), and **Financial Value** (cost-effectiveness).

### 8. Saving the Network at "Ava Telecom"
* **Link:** [https://quera.org/contest/assignments/84381/problems/308145](https://quera.org/contest/assignments/84381/problems/308145)
* **Description:** A large-scale **time-series forecasting** problem. "Ava Telecom" needs to manage its network resources due to massive traffic growth. The task is to predict the *total hourly* network traffic for the *entire next 30 days*. The model must be trained on historical data from ~370 customers, which is provided in *15-minute intervals*. The model must, therefore, aggregate and forecast from 15-min intervals to hourly predictions. The model is evaluated using **Root Mean Squared Error (RMSE)**.
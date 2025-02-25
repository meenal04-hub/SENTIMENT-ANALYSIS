# SENTIMENT-ANALYSIS

**TOPIC** : Women's E-Commerce Clothing Reviews

**COMPANY** : CODTECH IT Solutions

**NAME** : Meenal Gaikwad

**INTERN ID** : CT6WLXP

**DOMAIN** : Data Analytics

**DURATION** : 6 weeks

**MENTOR NAME** : Neela Santhosh Kumar

**DESCRIPTION** :

# Women's E-Commerce Clothing Reviews

**1. Introduction**

This project focuses on performing sentiment analysis on customer reviews collected from an e-commerce platform specializing in women's clothing. The dataset contains valuable insights, including customer ratings, review text, age, department name, and more. By analyzing these reviews, we can understand customer satisfaction, brand perception, and shopping experience.

**Objective**

The primary goal of this project is to build an NLP-based machine learning model that can automatically classify customer reviews as positive or negative, helping e-commerce platforms analyze customer feedback efficiently.

**2. Dataset Overview**

The "Women's Clothing E-Commerce Reviews" dataset contains:

* Review Text → Customer feedback on clothing items.
* Rating → A numerical rating given by the customer.
* Age → Age of the reviewer.
* Department Name → Clothing category.
* Class Name → Subcategory of clothing.
  
Each review provides feedback on specific clothing items, brands, or overall shopping experiences, reflecting customer sentiment towards the products and services offered by the platform.

**3. Project Workflow**

The project follows these key steps:

1️⃣ Data Collection

The dataset was obtained from an e-commerce platform specializing in women's clothing reviews.

2️⃣ Data Exploration & Cleaning

* Exploratory Data Analysis (EDA) was conducted to understand the dataset structure.
* Missing values were handled.
* Irrelevant data was removed.
* Text data was cleaned for NLP processing.
  
3️⃣ Text Preprocessing

To prepare the text for analysis, the following preprocessing steps were applied:

✔ Lowercasing → Converting text to lowercase.

✔ Removing Punctuation → Eliminating unnecessary symbols.

✔ Stopword Removal → Filtering out common words like "the", "and", etc.

✔ Tokenization & Lemmatization → Breaking text into words and converting them to base forms.

4️⃣ Feature Engineering

* TF-IDF (Term Frequency-Inverse Document Frequency) was used to convert text data into numerical representations.
  
5️⃣ Model Building

Several machine learning models were tested, with Logistic Regression being the final selected model:

✔ **TF-IDF Vectorization** was applied to transform text into feature vectors.

✔ **Logistic Regression Model** was trained to classify reviews as positive or negative.

6️⃣ Model Evaluation

The model's performance was evaluated using:

* Accuracy
* Precision & Recall
* F1 Score
* Confusion Matrix

Visualization techniques, including sentiment distribution plots and confusion matrices, were used to analyze model performance and sentiment trends in customer reviews.

**4. Results & Insights**

* The logistic regression model successfully classified customer reviews with high accuracy.
* Most customer reviews were positive, indicating high satisfaction levels.
* Negative reviews provided insights into common product complaints and customer dissatisfaction factors.
  
**5. Tools & Technologies Used**

* Python
* Natural Language Processing (NLP)
* Pandas & NumPy → Data handling & preprocessing
* Scikit-Learn → Machine learning models
* NLTK & SpaCy → Text preprocessing & tokenization
* Matplotlib & Seaborn → Data visualization

**6. Conclusion**

This project demonstrates the power of Natural Language Processing (NLP) in analyzing customer sentiment in e-commerce reviews. By classifying feedback as positive or negative, businesses can gain actionable insights to improve product offerings, enhance customer experience, and optimize marketing strategies.



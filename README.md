# NLP_transformer_model_article-topic-detector
"A machine learning-powered solution to automatically categorize news articles into relevant topics like sports, politics, and business."
## 🛠️ Skills & Technologies Used

### 🔹 Natural Language Processing (NLP)
- Text cleaning, tokenization, and preparation of textual data for modeling.

### 🔹 Text Classification
- Supervised learning to assign predefined categories to news articles.

### 🔹 Transformer Models / Large Language Models (LLMs)
- Utilized **FLAN-T5** for advanced contextual understanding and classification.

### 🔹 Machine Learning Algorithms
- Implemented **Random Forest** (Baseline, Tuned, and Class Weight variants).
- Evaluated models using **Accuracy, Precision, Recall, and F1-score**.

### 🔹 Sklearn Ecosystem
- Used for traditional ML models, preprocessing, and model evaluation.

### 🔹 Model Interpretability
- Confusion matrices, classification reports, and metric-based analysis.

### 🔹 Matplotlib & Seaborn
- Visualized distributions, patterns, and EDA insights.

### 🔹 Pandas & NumPy
- Efficient data manipulation and numerical operations.

### 🔹 Prompt Engineering
- Designed and tested custom prompts to enhance FLAN model performance.

## 📰 Business Context

In the dynamic landscape of the media and news industry, the ability to swiftly categorize and curate content has become a strategic imperative. The vast volume of information demands efficient systems to organize and present content to the audience.

The media industry, being the pulse of information dissemination, grapples with the continuous influx of news articles spanning diverse topics. Ensuring that the right articles reach the right audience promptly is not just a logistical necessity but a critical component in retaining and engaging audiences in an age of information overload.

### 📌 Common Industry Challenges:
- **Information Overload:** The sheer volume of news articles makes manual categorization impractical.
- **Timeliness:** Delays in categorizing news articles can result in outdated or misplaced content.

---

## 🧩 Problem Definition

**E-news Express**, a news aggregation startup, faces the challenge of categorizing the news articles collected. With news articles covering **sports, business, politics**, and more, the need for an advanced and automated system to categorize them has become increasingly evident.

The manual efforts required for categorizing such a diverse range of news articles are substantial, and human errors in the categorization of news articles can lead to reputational damage for the startup. There is also the factor of **delays and potential inaccuracies**.

To streamline and optimize this process, the organization recognizes the imperative of adopting cutting-edge technologies, particularly **Machine Learning**, to automate and enhance the categorization of content.

As a data scientist on the E-news Express data team, the task is to analyze the text in news articles and **build a model for categorizing them**. The goal is to **optimize the categorization process**, ensuring timely and personalized delivery to the end users.

---

## 📂 Data Dictionary

| Feature   | Description                                |
|-----------|--------------------------------------------|
| Article   | The main body of the news article          |
| Category  | The category the article belongs to        |

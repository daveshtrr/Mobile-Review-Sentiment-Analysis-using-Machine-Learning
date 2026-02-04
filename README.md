# Mobile Review Sentiment Analysis using Machine Learning
## End-to-End NLP Project | Logistic Regression | TF-IDF | Business Insights | 87% Accuracy

### Project Overview
Customer reviews contain rich insights that go far beyond star ratings. However, manually analyzing thousands of reviews is inefficient and often inaccurate.

This project builds a Machine Learning-based Sentiment Analysis system capable of automatically classifying mobile phone reviews into:
- Positive
- Neutral
- Negative

The model extracts meaningful patterns from textual feedback and transforms them into actionable business insights for product teams, marketers, and decision-makers.

### Business Problem
Mobile brands receive massive volumes of customer feedback across regions and platforms. Relying solely on ratings often misrepresents true customer satisfaction.
#### Key Questions Solved:
1. Can sentiment be accurately predicted from review text alone?

2. Why do some low-rated phones still receive positive feedback?

3. What factors drive negative sentiment?

4. How does sentiment vary across price ranges and regions?

### Solution Approach

#### Data Analysis Pipeline
1. Exploratory Data Analysis
- Sentiment distribution analysis
- Rating vs sentiment comparison
- Regional brand perception
- Price bucket sentiment trends

2. Text Preprocessing
- Lowercasing & regex cleaning
- Stopword removal
- Lemmatization using NLTK

3. Feature Engineering
- TF-IDF Vectorization (5000 features)

4. Model Building
- Logistic Regression classifier
- Stratified Train-Test split

5. Model Evaluation
- Classification report
- Confusion matrix
- Performance analysis

### Model Performance
| Metric       | Result                                   |
| ------------ | ---------------------------------------- |
| **Accuracy** | **~87%**                                 |
| Precision    | Strong for Positive & Negative           |
| Challenge    | Neutral sentiment is hardest to classify |

Conclusion: Sentiment can be predicted reliably using textual data alone.

### Key Business Insights
- Customer ratings do NOT always reflect true sentiment
- Battery life and performance are the biggest drivers of negative reviews
- Premium phones receive harsher criticism due to higher expectations
- The same brand is perceived differently across regions

These insights can directly support:
- Product improvement strategies
- Pricing decisions
- Market positioning
- Customer experience optimization

### Tech Stack
#### Languages & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Matplotlib, Seaborn
- WordCloud
#### Machine Learning
- TF-IDF Vectorizer
- Logistic Regression
#### Concepts Applied
- Natural Language Processing (NLP)
- Feature Engineering
- Classification
- Model Evaluation
- Business Analytics

### 👨‍💻 Author

#### Soundharya Sundaram Iyer
#### Github Link: https://github.com/Soundharya09/Mobile-Review-Sentiment-Analysis-using-Machine-Learning

#### If you like this project, consider giving it a ⭐ on GitHub!

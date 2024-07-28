# Sentiment Analysis on All-New Fire HD 8 Tablet Reviews

## Objective
The objective of this project is to perform sentiment analysis on the reviews of the All-New Fire HD 8 Tablet to understand customer sentiments towards the product. By analyzing these reviews, we aim to identify the overall customer satisfaction and key factors influencing positive and negative sentiments.

## Dataset Overview
### Description
The dataset consists of reviews for the All-New Fire HD 8 Tablet, 8 HD Display, Wi-Fi, 16 GB - Includes Special Offers, Magenta, sold by Amazon. The reviews include various attributes such as product ratings, user recommendations, review titles, review text, and more.

### Dataset Fields
- **id**: Unique identifier for each review.
- **name**: Name of the product.
- **asins**: Amazon Standard Identification Number (ASIN) for the product.
- **brand**: Brand of the product.
- **categories**: Categories the product belongs to.
- **keys**: Keys associated with the product.
- **manufacturer**: Manufacturer of the product.
- **reviews.date**: Date when the review was posted.
- **reviews.dateAdded**: Date when the review was added.
- **reviews.dateSeen**: Dates the review was seen.
- **reviews.didPurchase**: Indicates whether the reviewer purchased the product.
- **reviews.doRecommend**: Indicates whether the reviewer recommends the product.
- **reviews.id**: ID associated with the review.
- **reviews.numHelpful**: Number of people who found the review helpful.
- **reviews.rating**: Rating given by the reviewer.
- **reviews.sourceURLs**: URLs to the review source.
- **reviews.text**: Text content of the review.
- **reviews.title**: Title of the review.
- **reviews.userCity**: City of the reviewer.
- **reviews.userProvince**: Province of the reviewer.
- **reviews.username**: Username of the reviewer.

## Project Workflow
1. **Data Cleaning and Preprocessing**: 
   - Load the dataset.
   - Handle missing values.
   - Normalize text (e.g., lowercasing, removing punctuation).

2. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of sentiments.
   - Analyze the frequency of words and other insights.

3. **Sentiment Labeling**:
   - Label the reviews with sentiment categories (positive, negative, neutral).

4. **Text Preprocessing**:
   - Tokenization.
   - Removing stop words.
   - Lemmatization.

5. **Feature Extraction**:
   - Convert text data to numerical data using TF-IDF.

6. **Model Selection**:
   - Train models like Logistic Regression, Naive Bayes, and SVM.
   - Evaluate their performance.

7. **Model Interpretation and Insights**:
   - Interpret model results using feature importance and SHAP values.

8. **Visualization and Reporting**:
   - Create visualizations for sentiment distribution, feature importance, and SHAP values.
   - Generate a comprehensive report.

## Results
- The Decision Tree Classifier has performed well with this dataset, effectively capturing the sentiment nuances in the reviews.

## Conclusion
The Decision Tree Classifier has demonstrated strong performance, making it a suitable choice for sentiment analysis in this context. The insights gained from this analysis can help Amazon and potential buyers understand customer opinions on the All-New Fire HD 8 Tablet.

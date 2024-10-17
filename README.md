# Restaurant-Review-Classification

<img src="https://github.com/user-attachments/assets/d00f2633-89dc-406b-a0a6-42400f7f486d" >

### Project Overview:
In this project, we developed a sentiment classification model specifically designed for restaurant reviews. Using Natural Language Processing (NLP) techniques and a Naive Bayes classifier, the goal was to accurately classify reviews as positive(1) or negative(0) based on their textual content.

#### Approach:
- **Data Preprocessing**: Utilized NLTK for text cleaning, including tokenization, stopword removal, and stemming using the Porter stemmer.
- **Negation Handling**: Implemented a method to handle negations, specifically phrases like "**<mark>not good, not satisfied</mark>**," which could mislead the model if simply relying on stopwords.
- **Model Training**: Trained a Naive Bayes classifier using a labeled dataset of restaurant reviews to learn the relationships between words and their sentiments.
- **Real-Time Testing**: Conducted tests using real-time review data to evaluate the model's performance and generalization capabilities.

### Impact

The project addresses a significant challenge in sentiment analysis: the accurate interpretation of negations and their effect on sentiment. By enhancing the preprocessing pipeline to account for phrases like "not good," the model can better classify sentiments, resulting in:

- **Improved Accuracy**: The adjustments to handle negations led to a noticeable increase in classification accuracy for reviews containing negative sentiments.
- **Practical Application**: This model can be applied in various real-world scenarios, such as improving customer feedback analysis for restaurants, helping business owners understand customer satisfaction levels, and enhancing recommendation systems.

### Conclusion

The Restaurant Review Classification project demonstrates the importance of effective text preprocessing and the consideration of linguistic nuances, such as negations, in sentiment analysis. Despite challenges posed by limited training data, the implementation of custom cleaning methods significantly improved the model's performance. The successful handling of real-time data highlights the model's practical relevance in understanding customer sentiments, making it a valuable tool for restaurant owners and stakeholders.

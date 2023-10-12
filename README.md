# Reddit-Trending-Topics-Bot-with-Topic-Classification

## Objective
The Reddit Trending Topics Bot with Topic Classification aims to address the question: "How can we provide Reddit users with more informative and categorized summaries of the most discussed topics on the platform?"

## Scope of the project

### Authentication
To access Reddit data, we utilize OAuth2 authentication to obtain the necessary API credentials.

### Data Collection
The bot collects data by monitoring the specified subreddits, focusing on hot and trending posts.

### Topic Classification
Topic classification is achieved using machine learning, specifically the Multinomial Naive Bayes classifier from scikit-learn. Users can customize and expand this classification model based on their preferences.

### Scheduled Tasks
The bot schedules daily or weekly summary posts using the `schedule` library. Users can easily adjust the scheduling settings as needed.

### Error Handling
A robust error-handling mechanism is in place to address issues related to API requests, data parsing, and posting.

## Results
The Reddit Trending Topics Bot delivers daily or weekly summary posts to the specified subreddit. These summaries are enhanced with topic classification for the identified trending topics, providing users with categorized insights into the most discussed subjects.

## Evaluation and Quality Assurance

### Machine Learning Enhancement
The inclusion of a machine learning-based topic classification model allows for improved relevance and categorization of trending topics.

### Ongoing Development
The bot's machine learning model can be refined and expanded upon to enhance topic classification accuracy.

## Dependencies

- PRAW (Python Reddit API Wrapper)
- scikit-learn (for topic classification)
- schedule (for task scheduling)

## Conclusion

In conclusion, the Reddit Trending Topics Bot with Topic Classification is an exciting project that has the potential to significantly enhance the Reddit user experience. By addressing the need for more informative and categorized summaries of trending topics, we aim to empower users with a tool that provides greater insight into the most discussed subjects on the platform.



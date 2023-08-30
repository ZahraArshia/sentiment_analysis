# Sentiment Analysis with ParsBERT
Sentiment analysis is the process of analyzing digital text to determine if the emotional tone of the message is positive, negative, or neutral. Today, companies have large volumes of text data like emails, customer support chat transcripts, social media comments, and reviews. Sentiment analysis tools can scan this text to automatically determine the author’s attitude towards a topic. Companies use the insights from sentiment analysis to improve customer service and increase brand reputation.

![image](https://github.com/ZahraArshia/sentiment_analysis/assets/78906545/9642fc9e-29b6-41a4-81ab-72c2edd3d866)

## Dataset
[Digikala Comments Dataset](https://www.kaggle.com/datasets/soheiltehranipour/digikala-comments-persian-sentiment-analysis) is all about comments in the Digikala website site. These comments are scraped from Digikala.com and have been labeled based on the stars people who had bought the products gave to them. Also, many of the comments are noisy and do not provide clean data and it is not such a reliable source by adding the second label to the data we can ensure a higher accuracy of our training data. 

## ParsBERT
[ParsBERT](https://github.com/hooshvare/parsbert) is a monolingual language model based on Google's BERT architecture. This model is pre-trained on large Persian corpora with various writing styles from numerous subjects (e.g., scientific, novels, news, ...) with more than 3.9M documents, 73M sentences, and 1.3B words.

## Getting Started

### Prerequisites

In order to run this project you need to install the required packages:

```sh
!pip install transformers
!pip install hazm
!pip install clean-text[gpl]
```
### Setup
Clone this repository to your desired folder:

```sh
  cd your folder
  git clone git@github.com:ZahraArshia/sentiment_analysis.git
```

## Results

## Author

**Zahra**

- GitHub: [@githubhandle](https://github.com/ZahraArshia)
- LinkedIn: [LinkedIn](https://linkedin.com/in/ZahraArshia)

## Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/ZahraArshia/sentiment_analysis/issues).

## Show your support
If you like this project please give me a ⭐

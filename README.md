# Sentiment Analysis of Disney Parks Reviews
Disneyland Parks are hygely popular globally and garner plenty of reviews from parkgoers.  The aim of this project is to use Natural Language Processing and Unsupervised Learning exploration of all the reviews on the Disney Parks from California, Paris, and Hong Kong to gain insight into the overall sentiment of Disney parkgoers.  To dive even deeper, we'll try to gain insight as to why reviews are positive or negative by extracting key words and performing basic topic modeling.

## Data
A dataset of over 42,000 reviews on Disney Parks from California, Paris, and Hong Kong was obtained from Kaggle.  Reviews consisted mainly of textual data.  Each row consisted of a unique review, along with its unique ID, reviewer, date, Disney Park being reviewed, and a Rating score from 1 to 5.

## Tools and Algoirthms
For text processing: Python libraries/tools (NLTK, spaCy, Sklearn), Regex

For visualizations: Matplotlib, Seaborn, WordCloud, Scattertext

For topic Modeling: CorEx, Latent Semantic Analysis (LSA), Non-negative Matrix Factorization (NMF)

For sentiment analysis: VADER

## Key Takeaways
Sentiment Analysis: The reviews are significantly positive! Even the average sentiment score of all the 'negative' reviews is positive (although barely, at 0.05857), which shows that the overall sentiment of even the negative reviews aren't too negative.

By extracting key words, we see that reviewers describe the parks positively with words, such as: 'amazing', 'best', 'magical', 'clean', and 'fun'.  In contrast, reviewers also described the parks negatively with words, such as: 'rude', 'disappointed', 'bad', 'poor', 'crowded'.  There are many overlapping top key terms, and so further analysis into the context of the words is warranted to fully understand the scope/tone of all the reviews.

With a quick dive into topic modeling, we find that:
1. Reviewers like the California park and describe it as 'original'
2. Reviewers find the Paris park just 'typical' and the same as in the States
3. Reviewers thought the Hong Kong park was 'small'
4. Reviewers hated the fact that the food was 'expensive' and 'overpriced'
5. Reviewers enjoyed the parades and shows and thought they were 'amazing'

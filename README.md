# NLP_disasterTweets_LR_LGBM
Problem Statement: https://www.kaggle.com/competitions/nlp-getting-started/overview
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. Take this example:


The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

In this competition, you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. You’ll have access to a dataset of 10,000 tweets that were hand classified. If this is your first time working on an NLP problem, we've created a quick tutorial to get you up and running.

Disclaimer: The dataset for this competition contains text that may be considered profane, vulgar, or offensive.

💡Getting Started Notebook
To get started quickly, feel free to take advantage of this starter notebook.

Acknowledgments
This dataset was created by the company figure-eight and originally shared on their ‘Data For Everyone’ website here.

Tweet source: https://twitter.com/AnyOtherAnnaK/status/629195955506708480

## score
# LogisticRegression
Validation Accuracy: 0.7833
Validation F1 Score: 0.7321
Cross-Validation F1 Score: 0.5760 ± 0.0680
Average cross-validation accuracy: 0.6731968769709828

# LightGBM
Validation Accuracy: 0.7617
Validation F1 Score: 0.6998
Cross-Validation F1 Score: 0.5037 ± 0.0675


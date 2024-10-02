# 2024 Presidential Debate

## Overview
This project applies Natural Language Processing (NLP) techniques to analyze the 2024 U.S. Presidential Debate between Kamala Harris and Donald Trump. The goal is to derive insights from the candidates' speeches and sentiment trends.

## Table of Contents
* [Summary](#summary)
* [Data Source](#data-source)
* [Dependencies](#dependencies)

## Summary
With election day approaching, I conducted a natural language processing (NLP) analysis of the recent debate between the two presidential candidates. Using Python-based NLP tools, I examined the content of the debate to uncover insights into their language.
During the analysis, I discovered some interesting findings about each candidate’s speech. Here are a few insights I'd like to share:

1. How many words were used in the debate?
   
   During the debate, Kamala Harris spoke a total of 32,846 words, while Donald Trump used 43,217 words. Combined, the two candidates contributed a total of 76,063 words throughout the debate.

2. Sentiment Analysis

   The data frame below highlights an interesting observation: Kamala Harris exhibited a lower overall negative sentiment in her debate responses compared to Donald Trump, who displayed a higher level of negative sentiment. However, both candidates largely maintained a neutral tone throughout the debate.

   ![image](https://github.com/user-attachments/assets/e373af70-5c75-4a8d-8056-3f959f2c8ea9)


3. Topics and Sentiments

   The data frame below illustrates the sentiment of each candidate on various debate topics. Kamala Harris expressed negative sentiment when discussing 'Afghanistan,' while Donald Trump showed negative sentiment during the debate on the 'Israel-Hamas War.'
   On the other hand, Kamala Harris had a positive sentiment when addressing 'Policy Position Changes,' and Donald Trump displayed a positive sentiment when debating the 'Economy.'

   ![image](https://github.com/user-attachments/assets/c0ba3c50-9af0-46cc-8f32-a199d125815e)

5. Grammar

   On average, Kamala Harris made 3 grammatical errors per debate section, while Donald Trump averaged 6.5 errors. The maximum number of grammatical errors for each candidate was 7 for Harris and 17 for Trump.

6. Most Used Nouns and Verbs

   Below are the word clouds for each candidate.

   <p align="center">
  <img src="https://github.com/user-attachments/assets/5242961b-14b4-4ce5-a2fe-cf5e19e3fa46" width="45%" />
  <img src="https://github.com/user-attachments/assets/a69c2de8-c2bf-494d-991a-b99f54e51b18" width="45%" />
</p>

  <img src="https://github.com/user-attachments/assets/9bcd80ff-c7c5-4250-ae68-f29e7bc423fc" width="45%" />
  <img src="https://github.com/user-attachments/assets/1ddf292f-2078-464b-88cd-ff24fcea778c" width="45%" />
</p>


## Data Source
Data was from the abc news [link]([https://github.com](https://abcnews.go.com/Politics/harris-trump-presidential-debate-transcript/story?id=113560542)).

## Dependencies
This project is created with:
- nltk version 3.8.1

# Online QA System 

## Wiki QA 

Basic QA system in base language English, implemented using the MediaWikiAPI 

Retrieves wikipedia entries using keywords in the question, then gets answers from top 10 related paragraphs across chosen entries 


Type either keywords only or the entire question itself 

Does not yet work for yes/no questions like "Is Australia a Continent?" 

Example questions that work: What is the capital of Assam?, Who is the Greek goddess of Wisdom?, Where is Addis Ababa? 

Example questions that don't work: Who played Harley Quinn in the Suicide Squad?, What is a binary search tree? Who is the CEO of Apple? 


Need to modify model used to derive answers from context to increase accuracy, will try out NLG for answers as well 


## CQA 

Compares questions with preexisting questions in the datasets used to return an answer 

Uses the Yahoo! Answers Dataset for cQA - 2010 and the Yahoo! Answers Topic Classification Dataset - 2007 

Combinations of cosine similarity, levenshtein distance and the dice metric were used as similarity measures to compare question similarity and all approaches were evaluated using F-score 

Cosine Similarity + Word-Based Levenshtein Distance with final value as count × dice metric achieved the highest F-score of 0.99875 

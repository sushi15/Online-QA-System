#Online QA System 

## Wiki-QA 


Basic QA system in base language English, implemented using the MediaWikiAPI 

Retrieves wikipedia entries using keywords in the question, then gets answers from top 10 related paragraphs across chosen entries 


Type either keywords only or the entire question itself 

Does not yet work for yes/no questions like "Is Australia a Continent?" 

Example questions that work: What is the capital of Assam?, Who is the Greek goddess of Wisdom?, Where is Addis Ababa? 

Example questions that don't work: Who played Harley Quinn in the Suicide Squad?, What is a binary search tree? Who is the CEO of Apple? 


Need to modify model used to derive answers from context to increase accuracy, will try out NLG for answers as well soon

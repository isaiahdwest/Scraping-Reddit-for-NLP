# Do or do not: This is a Binary Classification
*Isaiah Westphalen*
_____
 **Background:** 
 Reddit is a social media site that collects forums dedicated to specific subjects where users can publish images, text, and videos. Each specific forum is referred to as a subreddit, and is dedicated to the discussion of one subject. 

**Objective:** 
 Using posts and comments from r/prequelmemes and r/marvelmemes we can develop a model in order to figure out what types of subjects users might be interested in based on samples of their text. 

**Methods:**
 - Using Psuhift's API, scrape posts/comments from r/prequelmemes and r/marvelmemes
 - Clean the data
 - Utilize CountVectorizer to get text data into a model ready format
 - Using a RandomForestClassifier, Logistic Regresssion, and a GridSearch create a model that can classify which reddit a text sample belongs to
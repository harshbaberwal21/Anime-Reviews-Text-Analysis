# Anime-Reviews-Analysis
### Text Mining - Academic Project



## Description
The anime viewership is growing at an ever-increasing pace, owing to the increasing number of new anime catering to everyone’s interests, widespread adoption of anime by major streaming platforms such as Netflix. This along with the success and popularity of the AT&T owned anime streaming platform, Crunchyroll, this industry is growing bigger and bigger. Today Netflix houses not only mainstream anime but also launches the up-and-coming ones to maintain the interest of viewers. With this budding popularity and growing market size, it is important to understand what the audience is looking for in anime.



## Intention
In this project, we tend to use the viewer’s reviews and analyze them to identify what anime characteristics do people appreciate the most (through positive reviews) and what others they find crucial to be improved (through negative reviews). To carry out this research, action and romance are chosen to be the two genres to be studied. The rationale behind it is that these are two of the most reviewed genres and are the most distinct from each other in terms of content compared to others. Moreover, the compatibility of our data and research question restricted us to using these two genres.  


## Data
The reviews being studied are scraped from myanimelist.com website that houses the anime community and discussions around multiple anime. The data contains 3 files; reviews, anime and profile. Reviews dataset has the reviews text aloing with anime-id and review-id. The anime dataset contains anime metadata such as anime genre.  


## Output Overview
The primary output of this exercise are wordclouds (with importance-weighted size) for positive/negative reviews for both the genres. 
With better data quality and additional efforts directed towards data cleaning and processing, other forms of the output could be computed depending upon the use case.  

Below is a wordcloud of the most appreciated characteristics of anime of action genre.
![Wordcloud](https://github.com/harshbaberwal21/Anime-Reviews-Text-Analysis/blob/c159adb292bd655c4511c9073c2d2a5eea4e8741/WordClouds/wordcloud_action_pos.png)
 


## RawData Used


##### Kaggle Dataset Link (might have been updated):
https://www.kaggle.com/marlesson/myanimelist-dataset-animes-profiles-reviews?select=reviews.csv. 

##### Drive Link (The exact dataset used):
https://drive.google.com/file/d/1xm7liUUvJHcOddy6b3Bnoatybc7OPClN/view?usp=sharing



##### Note: In addition to solving a crucial business problem, the intent of the academic project was to understand the text processing and classification principles and hence, the topic chosen was strictly interest based and the notebook is built as a one time activity.

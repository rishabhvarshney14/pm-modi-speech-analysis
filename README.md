# PM Narendra Modi's Speech Analysis

Narendra Modi is the 14th and current Prime Minister of India. He has given numerous speeches not only in India but also outside India.

In this we are going to analyze speeches of PM Narendra Modi.

## Data

Data : All the data has been collect from Mr. Narendra Modi's [website](https://www.narendramodi.in/)

The data contains speeches from April 2, 2016 to June 16, 2020

I have collected data and stored it into 2 csv file:
  - speech_with_hindi.csv : This is raw data that I have collected it contains four columns 'headings', 'dates', 'articles' and 'tags'.
  - speech_without_hindi.csv : This is the data where I have translated speeches from hindi to english and drop all the rows where the speech does not properly translated it has the same columns as speech_without_hindi.csv
  
There are 960 rows in speech_with_hindi and 870 rows in speech_without_hindi.

## Analysis

From April 2, 2016 to June 16, 2020 Mr. Narendra Modi has given 960 speeches (provided on his website).

Let's have a look on speeches given per year:
 
 ![speeches per year](https://github.com/rishabhvarshney14/pm-modi-speech-analysis/blob/master/images/speech_per_year.png)
 
Looking at both of the plots we can see that there are not much different between these two so we are going to only use speech_with_hindi.csv for exploration while I will use the other one for text generation.

From the plot we can see that the number of speeches given in 2019 is the highest where as it is less in 2020 (it is because the data only contains speech till June 2020).

![wc_all](https://github.com/rishabhvarshney14/pm-modi-speech-analysis/blob/master/images/wc_all.png)

Let's have a look on the tags that have been used mose frequently

Apart from the words like Speeches, India, National the most frequent words are 'Development', 'Infrastructure', 'Empowering the Poor', 'Technology', 'Yuva Shakti', 'Youth', 'Education', 'Farmers' and 'Healthcare'

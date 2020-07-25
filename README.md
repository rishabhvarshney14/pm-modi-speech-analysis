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

![fot_all](https://github.com/rishabhvarshney14/pm-modi-speech-analysis/blob/master/images/fot_all.png)

### Internation speeches given

As of July 2020, Narendra Modi has made 59 foreign trips, visiting 60 countries including the visits to USA to attend the UN General Assembly, to Asian countries, following his neighbourhood first and act east policies.

He has given 34 speeches outside India between April 2, 2016 to June 16, 2020.

![spy_international](https://github.com/rishabhvarshney14/pm-modi-speech-analysis/blob/master/images/spy_international.png)

Due to covid 19 He has not given any speech outside India this year.

Lets have look on how much speeches he has given country-wise (not including India)

![speech_given_country](https://github.com/rishabhvarshney14/pm-modi-speech-analysis/blob/master/images/speech_given_countries.png)

Seems like he has given more speeches in Africa, Singapore and Saudi Arabia than any other country. 

Speech given is Mexico is "Howdy, Modi!" given in September 3, 2019 also the conversation between Mr. Narendra Modi and Mr. Mark Zuckerberg was held in September 28, 2015 so it was not included here.

Let's have a look at frequencies of tags:

![fot_international](https://github.com/rishabhvarshney14/pm-modi-speech-analysis/blob/master/images/fot_international.png)

Tags like "Development", "Infrastructure", "Empowering the Poor", "Technology" and "Yuva Shakti" are commonly used.

### Mann Ki Baat 

Mann Ki Baat is an Indian radio programme hosted by Prime Minister Narendra Modi in which he addresses the people of the nation on All India Radio, DD National and DD News. Since the first show on 3 October 2014, there have been 66 episodes. The 66th episode was aired on 28 June 2020.

Mann Ki Baat does not considered as a speech but it is included in the website's speech section so we also take it here.

According to the survey done by AIR maximum listeners came from the Bihar, Gujarat and Madhya Pradesh while the states of Andhra Pradesh and Arunachal Pradesh had the lowest awareness.

![spy_mann_ki_baat](https://github.com/rishabhvarshney14/pm-modi-speech-analysis/blob/master/images/spy_mann_ki_baat.png)

Word cloud of Mann Ki Baat:

![wc_speech_mann_ki_baat](https://github.com/rishabhvarshney14/pm-modi-speech-analysis/blob/master/images/wc_speech_mann_ki_baat.png)

Hindustan Times also did a word cloud analysis of Mann Ki Baat.The words "India" and "nation" were the two most used words in Mann Ki Baat in 2019. "Youth" and "Young" were mentioned 30 and 54 times. "Economy" or "economics" was spoken 8 times.

![fot_mann_ki_baat](https://github.com/rishabhvarshney14/pm-modi-speech-analysis/blob/master/images/fot_mann_ki_baat.png)

The most used tags in Mann ki Baat are "Development", "Infrastructure", "Empowering the Poor", "Technology", "Education", and "Human Development".

### Year wise Analysis

In this we will consider all speeches inluding international and Mann ki Baat.

#### 2016

